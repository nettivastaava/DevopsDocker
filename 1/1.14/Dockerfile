FROM ruby:2.6.0

WORKDIR /app
COPY rails-example-project .
RUN apt-get update
RUN apt-get install -y nodejs
RUN gem install bundler && bundle install
RUN rails db:migrate
CMD rails s
