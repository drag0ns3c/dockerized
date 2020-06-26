FROM alpine:latest

RUN apk update && apk upgrade

WORKDIR /hydra

RUN apk add git openssl-dev make libssh-dev build-base

RUN git clone https://github.com/vanhauser-thc/thc-hydra.git && \
    cd /hydra/thc-hydra && ./configure && make && make install

ENTRYPOINT [ "/usr/local/bin/hydra" ]
