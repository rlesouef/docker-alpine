FROM alpine:3.6
MAINTAINER Open Source Services [os2.fr]

ENV PACKAGES tini

RUN apk update && \
    apk upgrade && \
    apk add $PACKAGES && \
    rm -rf /var/cache/apk/*

ENTRYPOINT ["/sbin/tini", "--"]
CMD ["sh"]
