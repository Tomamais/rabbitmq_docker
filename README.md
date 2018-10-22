# RabbitMQ Docker templates
###A couple of files to build, config and run RabbitMQ containers.

This repo contains:

- Dockerfile - the rabbitmq container definition
- rabbitmq.config - rabbitmq configuration file (copied to the image on build time)
- definitions.json - rabbitmq definitions (users, hosts) referenced in configuration file (copied to the image on build time)
- docker-.compose.yml - The file the puts everything together
- clean/docker-compose.yml - The simpliest possible rabbitmq configuration container