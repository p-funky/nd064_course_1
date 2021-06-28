FROM golang:alpine

LABEL maintainer="Adeyinka Alabi"

WORKDIR /go/src/app

ADD . /go/src/app

RUN go mod init

RUN go build -o helloworld

EXPOSE 6113
# provide a command to run on container start. 
# For example, start the `app.py` application.
CMD [ "./helloworld" ]
