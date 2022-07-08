# sysdig-hello-world-nodejs

# UPDATE - WIP

repo with a test container image to test vulnerabilities pipeline scanning

Sample node app that runs a simple express webserver on port 3030 - Includes a third party library (logrus) for scanning demonstration purposes

## Setup

`docker run --name sysdig-hello-world-nodejs -p 3030:3030 ghcr.io/bashfulrobot/sysdig-hello-world-nodejs:latest`
