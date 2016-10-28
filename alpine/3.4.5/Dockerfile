FROM alpine:3.4.5

MAINTAINER Gergely Nemeth <gergely@risingstack.com>

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
