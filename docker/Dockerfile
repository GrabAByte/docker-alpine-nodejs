FROM grababyte/alpine-base:0.7.3

LABEL devops.grababyte.image.authors="GrabAByte"

RUN \
  apk add --no-cache \
    nodejs==14.19.0-r0 \
    npm==7.17.0-r0 && \
  rm -rf /var/cache/apk/*
