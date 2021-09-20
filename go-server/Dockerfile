FROM golang:bullseye

WORKDIR /app

COPY  go.mod .

COPY go.sum .

RUN go mod download

COPY . .

EXPOSE 9090

RUN go build -o main .

CMD ["./main"]