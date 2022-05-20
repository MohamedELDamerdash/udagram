@First, the circleci will connect to the developer GitHub account, which it will verify every time we push code or make a change.

@The circleci/config.yml file is read by Circlci.

@Starting with orb, which will setup the project in this case by installing node.js, aws cli, and elastic beanstalk.
The programme will then be run using the commands provided:
    @@ Install the frontend and backend packages first . After that, the frontend and backend components will be built, and the application will be deployed.