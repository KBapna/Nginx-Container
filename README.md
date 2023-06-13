# Nginx Container
This is a pre configure Nginx container
## Usage

You need to populate the container with custom NginX configuration files since they have been removed from the image:
```
/etc/nginx/nginx.conf
/etc/nginx/conf.d/*.conf
```
See in this example how to configure the deployment for that purpose: [docker-compose.yaml](etc/swarm/nginx.yaml)
