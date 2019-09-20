FROM debian:buster-slim

RUN apt-get update && \
  apt-get upgrade -y && \
  apt-get install -y curl

RUN curl -L -O https://project-downloads.drogon.net/wiringpi-latest.deb && \
  dpkg -i wiringpi-latest.deb

ENTRYPOINT ["gpio"]

CMD ["readall"]

