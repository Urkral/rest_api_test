FROM ubuntu:latest

RUN apt-get update && apt-get install nano sl -y

WORKDIR /usr/games

COPY script.sh .

RUN chmod +x script.sh
ENV NUMBER=2

ENTRYPOINT [ "./script.sh" ]