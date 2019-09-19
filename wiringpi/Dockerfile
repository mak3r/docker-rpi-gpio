FROM raspbian/stretch

RUN apt-get update && \
  apt-get upgrade -y && \
  apt-get install -y wiringpi

ENTRYPOINT ["gpio"]

CMD ["readall"]





