FROM golang:1.18-alpine
WORKDIR /app

COPY . .

RUN go mod download
RUN go build .

EXPOSE 3000

CMD ["./backend"]