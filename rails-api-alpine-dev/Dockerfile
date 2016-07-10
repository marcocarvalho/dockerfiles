FROM ruby:2.3.1-alpine

apk add --no-cache --virtual postgresql-client
apk add --no-cache --virtual build-dependencies
apk add --no-cache --virtual build-base
apk add --no-cache --virtual ruby-dev
apk add --no-cache --virtual openssl-dev
apk add --no-cache --virtual libstdc++
apk add --no-cache --virtual tzdata
apk add --no-cache --virtual zlib
apk add --no-cache --virtual libxml2
apk add --no-cache --virtual libxslt

ENV RAILS_VERSION 5.0.0

RUN gem install rails --version "$RAILS_VERSION"
