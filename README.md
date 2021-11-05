# IT5007_Tutorial_5

Tutorial 5 Submission 

Done by: Benjamin Aw A0124029N

Instructions to set up environement:

Assumption: npm, git and mogo are set up in environment already.

1) Expose both port 5000 and 3000 for API and UI server respectively
2) Pull the files into the home directory 
3) Start up mogodb in API folder
    - Using command: screen mongod
    - Initialise first 3 entries in database: mongo custtracker scripts/init.mongo.js
4) Start API
    - cd to API folder
    - Run npm install
    - npm start to load at localhost:5000
5) Start UI
    - Open an new terminal 
    - cd to UI folder
    - Run npm install
    - npm start to load at localhost:3000
