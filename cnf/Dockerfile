FROM wordpress:latest

ARG WWWGROUP

ENV TZ=UTC
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

# RUN apt-get install -y nodejs
