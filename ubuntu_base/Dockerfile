FROM ubuntu:latest

RUN apt-get update && apt-get -y --no-install-recommends install gosu

COPY entrypoint.sh /usr/local/bin/entrypoint.sh

ENTRYPOINT ["/usr/local/bin/entrypoint.sh"]
