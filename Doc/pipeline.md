
GitHub :The engineers contribute and push their code to the CircleCI platform's GitHub repository. When code is pushed to GitHub, the CircleCI platform is triggered.


CircleCI: .circleci/config.yml file is read by CircleCI and tells the service what to do. In the instance of Udagram, CircleCI is deploy and bulid backend and frontend.


Frontend: Executes the package.json file's build script. The assets are then uploaded to S3 using the AWS CLI.

Backend: Runs the build script, then exports all CircleCI setup environment variables to a.env file before running the archive script. The archive is then uploaded to S3 using AWS CLI.
