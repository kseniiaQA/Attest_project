## to start docker container with tests copy a directory: 
### https://github.com/kseniiaQA/Attest_project.git



## then go to a directory (cd/.../Attest_project) and run a command to upload a docker container for cypress test run:
#### docker pull cypress/included:10.3.1


## then we run this image  in interactive mode 
####  docker run -it --entrypoint=cypress cypress/included:10.3.1 info


## then we execute an image for container 
#### docker run -it -v $(pwd):/Attest_project -w /Attest_project cypress/included:10.3.1 --spec cypress/e2e/spec.cy.js --browser chrome

  

