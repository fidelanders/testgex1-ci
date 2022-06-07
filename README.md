# testgex1-ci
Test pipeline deployment using GITHUB CI with node javascript and mocha

********************
Simple testing with passed and failed scenarios 

********************
## Procedure to use this repo

1. clone repo
2. select run python code on the command line 
(NB: This process is for vscode editor, you can use other text editor too)

# dev/docker-compose.yml
version: '3'
services:
  node:
    image: node:16
    volumes:
      - ./../:/project
    working_dir: /project