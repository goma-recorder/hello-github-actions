FROM alpine:3.9

RUN apk update && apk add bash git npm jq

ADD entrypoint.sh /entrypoint.sh

RUN chmod +x /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
