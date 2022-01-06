FROM golang:latest
COPY ./src/backend/ /app
WORKDIR /app
RUN go mod tidy
RUN go build -o main.go
# CMD ["/app/main"]