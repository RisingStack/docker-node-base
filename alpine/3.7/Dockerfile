FROM alpine:3.7

LABEL maintainer="Tamas Kadlecsik <tamas.kadlecsik@risingstack.com>"

RUN apk add --update \
	binutils-gold \
	ca-certificates \
	curl \
	git \
	gcc \
	g++ \
	libgcc \
	libstdc++ \
	linux-headers \
	make \
	paxctl \
	python

RUN update-ca-certificates
