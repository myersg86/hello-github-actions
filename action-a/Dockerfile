FROM ubuntu:18.04

RUN apt-get update -qq && apt-get install -y clamav
RUN freshclam --show-progress
