FROM ubuntu:20.04

WORKDIR /usr/src/app

RUN apt update 
RUN apt install curl 

COPY new_file.sh .

CMD ./new_file.sh
