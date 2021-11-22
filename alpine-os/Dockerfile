FROM alpine

RUN apk update

ARG DEBIAN_FRONTEND=noninteractive

RUN apk add python3 py3-pip ansible 

CMD while true; do pwd; sleep 60; done;
