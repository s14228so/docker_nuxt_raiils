FROM ruby:2.5.3
RUN apt-get update -qq && \
    apt-get install -y build-essential \ 
    libpq-dev \        
    nodejs     

WORKDIR /app

ADD ./Gemfile .
ADD ./Gemfile.lock .


RUN bundle install
ADD . $APP_ROOT
