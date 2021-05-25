FROM golang:latest

ENV REQUEST_ORIGIN=http://localhost:5000

WORKDIR /backend

COPY ./example-backend /backend

RUN go build

ENV PORT=8080 

EXPOSE 8080

CMD ["./server"]
