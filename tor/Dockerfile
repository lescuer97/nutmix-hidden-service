FROM alpine:latest

MAINTAINER GIT

RUN apk update && apk add --no-cache tor

COPY torrc /etc/tor/torrc
                    
CMD ["tor", "-f", "/etc/tor/torrc"]
