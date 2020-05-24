From alpine:latest

RUN apk add --no-cache nodejs npm

WORKDIR /app

copy ./app

RUN npm install

EXPOSE 9005

ENTRYPOINT ["node"]

cmd ["server.js"]