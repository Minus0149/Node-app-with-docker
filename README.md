# Node-app-with-docker

Run
`docker-compose -f docker-compose -f docker-compose.dev.yml up -d`
to run the Docker container in development mode.

Run
`docker-compose -f docker-compose -f docker-compose.prod.yml up -d`
to run the Docker container in production mode.

Run
`docker-compose -f docker-compose -f docker-compose.dev.yml down`
to stop the development Docker container.

Run
`docker-compose -f docker-compose -f docker-compose.prod.yml down`
to stop the production Docker container.

Note : add -v flag while deleting an container to remove all the volumes made by the containers
