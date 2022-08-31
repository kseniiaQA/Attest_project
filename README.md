## To start docker container with tests copy a directory: 
### https://github.com/kseniiaQA/attest_project.git



## Then go to a directory (cd/.../Attest_project) and run a command to upload a docker container for cypress test run:
#### docker pull cypress/included:10.3.1


## Then we run this image  in interactive mode 
####  docker run -it --entrypoint=cypress cypress/included:10.3.1 info


## Then we execute an image for container 
#### docker run -it -v $(pwd):/attest_project -w /attest_project cypress/included:10.3.1 --spec cypress/e2e/spec.cy.js --browser chrome

  

