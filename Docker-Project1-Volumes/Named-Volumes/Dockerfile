FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

VOLUME /var/lib/docker/volumes

CMD ["node", "server.js"]

