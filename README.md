# traefik

Simple skeleton setup for using traefik as proxy infront your normal docker-containers. 

just change the email address in traefik.yml file, create a docker network called 'traefik' and fire up the docker-compose.yml file to start your traefik container.

Then you can simply use the nginx.yml compose file to setup a normal nginx example behind the traefik container for testing, and then copy/paste the label values 
and network settings from the nginx.yml file into you own docker-compose.to have the container being served behind the traefik container
