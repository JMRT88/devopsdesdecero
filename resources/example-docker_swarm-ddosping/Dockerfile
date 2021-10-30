FROM ubuntu:20.04

RUN apt update
RUN apt install -y iputils-ping;

WORKDIR /app

COPY ddos-ping-script /app/ddos-ping
RUN chmod +x /app/ddos-ping

CMD [ "bash", "ddos-ping" ]
