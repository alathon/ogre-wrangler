FROM golang:1.18.1

ARG SERVICE

RUN mkdir /build
COPY . /build
WORKDIR /build
RUN go build -o /app ./cmd/$SERVICE

CMD ["/app"]
