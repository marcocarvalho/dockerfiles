FROM ruby:2.3.1-alpine

RUN apk add --no-cache --virtual postgresql-client build-dependencies build-base ruby-dev openssl-dev libstdc++ tzdata zlib libxml2 libxslt

ENV RAILS_VERSION 5.0.0

RUN gem install rails --version "$RAILS_VERSION"
