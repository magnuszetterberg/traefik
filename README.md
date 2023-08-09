# traefik

Simple skeleton setup for using traefik as proxy infront your normal docker-containers. 

Just change the email address in traefik.yml file, create a docker network called 'traefik' and fire up the docker-compose.yml file to start your traefik container.

Then you can pick and choose which .yml to run through your traefik proxy. Most of it should work out of the box, but just make sure to adjust eventual domains and email addresses where indicated in each file.

Used Christian Lempa's boilerplate setup for traefik to get this working availble here
https://github.com/ChristianLempa/boilerplates/tree/main/docker-compose/traefik
