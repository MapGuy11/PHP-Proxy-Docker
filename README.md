# PHP-Proxy-Docker


# Dockerfile (Build the image yourself)

1. clone the repo
2. docker build -t php-proxy .
Running 
1. docker run -i -t php-proxy


# Get From Docker Hub (Simple And Easy)
docker pull mapguysolutions/php-proxy-docker\
https://hub.docker.com/r/mapguysolutions/php-proxy-docker

# Ports

Ports | Reason | Options
--- | --- | ---
80 | HTTP Traffic| **Can Be Mapped Differently**
443 | HTTPS Traffic| **Can Be Mapped Differently**
