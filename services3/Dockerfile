FROM golang:1.10.5-alpine3.8

WORKDIR /opt/app-root/


COPY . .

RUN go build main.go

EXPOSE 8080

CMD ["./main"]