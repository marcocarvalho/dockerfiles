FROM ruby:2.3.1-alpine

RUN apk add --no-cache --virtual postgresql-client
RUN apk add --no-cache --virtual build-dependencies
RUN apk add --no-cache --virtual build-base
RUN apk add --no-cache --virtual ruby-dev
RUN apk add --no-cache --virtual openssl-dev
RUN apk add --no-cache --virtual libstdc++
RUN apk add --no-cache --virtual tzdata
RUN apk add --no-cache --virtual zlib
RUN apk add --no-cache --virtual libxml2
RUN apk add --no-cache --virtual libxslt
RUN apk add --no-cache --virtual postgresql-dev

ENV RAILS_VERSION 5.0.0

RUN gem install rails --version "$RAILS_VERSION"
