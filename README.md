What all you going to get in this repo....

docker-compose.yml 
-  this file is more likely to be pushed on production servers so there should not be any change in this file
you can take this a placeholder and the other files which we will talk later is actually dependent on this...

docker-compose-dev.yml
- this file is meant for local development not for production so any configuration in this file are 
expected to affect only local environment to have effect on local

docker-sync.yml
- this file contains configuration to sync container with the host system


Once you have all three files configured (mentioned above) then you are ready for work.

To start all the services (docker containers) you will execute
"docker-sync-stack start"

to stop
"CTRL + C"
