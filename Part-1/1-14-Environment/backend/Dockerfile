FROM ubuntu:20.10

EXPOSE 8080

ENV REQUEST_ORIGIN=http://localhost:5000

WORKDIR /go

COPY backend-docker .

RUN apt update && apt install -y golang-go ca-certificates

RUN go build

CMD ./server