FROM alpine:3.2

RUN echo "http://nl.alpinelinux.org/alpine/edge/main" | \
  tee /etc/apk/repositories \

  # Install packages
  && apk add --update \
    make \
    bash \
    python \
    nodejs \

  && rm -rf /var/cache/apk/* \

  # NodeJS
  && npm i -g nodemon

EXPOSE 5858
EXPOSE 3000

WORKDIR /app
