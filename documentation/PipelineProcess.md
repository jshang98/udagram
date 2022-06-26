# Pipeline Process

The pipeline is setup in CircleCI and connects with GitHub repository.

## Order of commands

1. The pipeline uses base image with NodeJS 14.19 and uses orbs to install AWS cli and the EB cli.
2. It checks out the code from the repository limited to main branch
3. FrontEnd & BackEnd install
4. FrontEnd & BackEnd build
5. FrontEnd & BackEnd deploy

## Schema

![Pipeline Schema](./images/pipelineprocess.png)