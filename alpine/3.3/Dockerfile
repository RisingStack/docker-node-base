FROM janeczku/alpine-kubernetes:3.3

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
