FROM golang:1.16

WORKDIR /usr/src/app

EXPOSE 8080

COPY ./example-backend/ /usr/src/app/

ENV REQUEST_ORIGIN=http://127.0.0.1:5001

RUN go build
RUN chmod +x server

CMD ["./server"]