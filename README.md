Feel free to fork this theme from Chirpy 

Have added a docker container & custom docker image to make my life easier, so that I don't have to install npm or it's dependencies onto my laptop. Everything runs inside docker.

To run the dev server - `docker compose up -d`

On changes to the `_config.yml` file ensure to restart the container with `docker compose restart`