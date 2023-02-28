FROM nginx:1.22-alpine
LABEL maintainer=""
SHELL ["/bin/ash", "-oeux", "pipefail", "-c"]
ENV TZ=Asia/Tokyo

RUN apk update && \
  apk add --update --no-cache --virtual=.build-dependencies g++

COPY ./docker/nginx/*.conf /etc/nginx/conf.d/
