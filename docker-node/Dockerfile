FROM alpine:3.2

RUN echo "http://nl.alpinelinux.org/alpine/edge/main" | \
  tee /etc/apk/repositories \

  # Install packages
  && apk add --update \
    nodejs \
    python \

  # NodeJS
  && npm i -g stream-adventure \
    nodemon \
    mocha \
    express-generator \
    istanbul

EXPOSE 80

WORKDIR /app
