FROM golang:1.17

RUN mkdir -p /app

WORKDIR /app

#ADD . /app
COPY . /app

RUN go mod tidy

RUN go build ./main.go

#EXPOSE 8080
CMD ["./main"]