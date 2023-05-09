FROM ubuntu:22.04

ENV HTTP_PROXY $HTTP_PROXY
ENV HTTPS_PROXY $HTTPS_PROXY
ENV http_proxy $http_proxy
ENV https_proxy $https_proxy

RUN apt update && apt upgrade -y
RUN apt install -y language-pack-ja-base language-pack-ja locales
RUN locale-gen ja_JP.UTF-8
ENV LANG ja_JP.UTF-8
RUN apt install emacs -y