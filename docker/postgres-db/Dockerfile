FROM postgres:latest

RUN apt-get update && \
    apt-get install -y locales locales-all && \
    locale-gen ja_JP.UTF-8 && \
    update-locale LANG=ja_JP.UTF-8

# Time ZoneAc
ENV TZ Asia/Tokyo

# Language
ENV LANG ja_JP.UTF-8
ENV LANGUAGE ja_JP:ja
ENV LC_ALL ja_JP.UTF-8