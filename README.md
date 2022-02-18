## Description
* Purpose of this script is to deploy WordPress using one command
* After deployment WordPress is available on http://localhost:8000/

# Prerequisites
* Linux machine
* install Docker https://docs.docker.com/engine/install/ubuntu/
* install Docker Compose https://docs.docker.com/compose/install/

Installation for Docker and Compose could be done using script setup.sh.<br>
To setup Docker and Docker compose:<br>
`chmod +x setup.sh`<br>
`./setup.sh`

## Deploy WordPress
`sudo docker-compose up -d`

## Destroy WordPress
`sudo docker-compose down`