FROM ubuntu:16.04

RUN apt-get update -y && apt-get install -y iputils-ping

ENTRYPOINT [ "ping" ]

CMD [ "8.8.8.8" ]