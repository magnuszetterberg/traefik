# traefik

Simple skeleton setup for using traefik as proxy infront your normal docker-containers. 

Just change the email address in traefik.yml file, create a docker network called 'traefik' and fire up the docker-compose.yml file to start your traefik container.

Then you can simply use the nginx.yml compose file to setup a normal nginx example behind the traefik container for testing, and then copy/paste the label values 
and network settings from the nginx.yml file into you own docker-compose.to have the container being served behind the traefik container

The nodered.yml has a basic auth setup also, which can be used in other docker-compose.yml files aswell.


Used Christian Lempa's boilerplate setup for traefik to get this working availble here
https://github.com/ChristianLempa/boilerplates/tree/main/docker-compose/traefik
