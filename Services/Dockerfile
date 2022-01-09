FROM golang:1.17 
WORKDIR /usr/app
COPY . .

WORKDIR /usr/app/product_service
RUN go run main.go

WORKDIR /usr/app/user_service
RUN go run main.go


