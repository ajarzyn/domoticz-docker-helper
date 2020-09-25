# domoticz-docker-helper
Helper script to build, create, test, and deploy domoticz images on server.

## Setup
Requirements are: `sshpass, ssh, scp, docker, id, pwd, grep, date`

If script does not have perrmission to run: `chmod +x domoticzDockerCreate`

## Run examples
Run script like this `./domoticzDockerCreate [params]`

Build image only `./domoticzDockerCreate -nc`

Deploy image docker/local:latest into server `./domoticzDockerCreate -nb -nc -ui`

If you want to create test container for python plugins debugging `./domoticzDockerCreate -nv -ct -dp`

