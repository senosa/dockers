FROM tdiary/tdiary:latest
MAINTAINER Sensuke Osawa <senosa@gmail.com>

COPY . /usr/src/app/
RUN bundle && bundle exec rake assets:copy
