FROM golang:1.16

WORKDIR /usr/src/app

EXPOSE 8080

COPY ./example-backend/ /usr/src/app/

RUN go build
RUN chmod +x server

CMD ["./server"]