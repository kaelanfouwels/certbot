FROM certbot/certbot:v1.9.0

RUN apk update && apk add --no-cache openssl certbot

COPY entrypoint.sh entrypoint.sh
RUN chmod +x ./entrypoint.sh

ENTRYPOINT ["./entrypoint.sh"]