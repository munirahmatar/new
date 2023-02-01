
Pipeline  Process

1- The developer update the code, commit the changes, and push to the GitHub repository.

2- The GitHub connected to CircleCi and Circleci follows the project and set up the environment variables.

3- The CirecleCI reads the .circleci/config.yml to perform the jobs that will run the scripts from package.json to install, build, and deploy the frontend and backend.

4- there's 3 process ( Build, Hold, Deploy).

5- The AWS will upload to S3 and backend to EBS.