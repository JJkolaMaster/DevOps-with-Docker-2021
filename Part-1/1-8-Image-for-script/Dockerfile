FROM ubuntu:18.04 
RUN apt update && apt install curl -y 
WORKDIR /usr/src/app 
COPY script.sh . 
CMD ./script.sh