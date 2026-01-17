FROM alpine:3.20

RUN apk add --no-cache tor

COPY torrc /etc/tor/torrc

CMD ["tor", "-f", "/etc/tor/torrc"]

