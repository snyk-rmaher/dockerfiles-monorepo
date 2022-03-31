FROM alpine:3.15.3
LABEL maintainer "Jessie Frazelle <jess@linux.com>"

RUN apk --no-cache add \
	bash \
	certbot

ENTRYPOINT [ "certbot" ]
