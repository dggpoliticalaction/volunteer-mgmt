### Install
* Follow the install process for both docker and docker compose for your machine.
### PreRun 
* Inorder to run the server, first clone [Our Fork of SuiteCRM](https://github.com/SuiteCRM/SuiteCRM-Core) under the folder name "www"
    * Note: Currenlty the link will direct you to the base SuiteCrm since we do not have a fork at this time.
Rename dockerfile_SUITECRM to just dockerfile, and move it to the www folder.
* CD into www
* run yarn merge-angular-json
### Run 
* Run: docker compose build
* Run: "docker compose up", in the folder where the docker compose file is
    * if you run into an error saying "cannot connect to the socket"
### Notes 
* Try: "sudo" if a docker command is giving issues 

