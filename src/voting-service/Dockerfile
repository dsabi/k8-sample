FROM docker.io/node:13-alpine

WORKDIR /app

COPY ./package.json ./

RUN npm install

COPY . .

EXPOSE 8080

CMD ["node", "index.js"]
#CMD ["node", "--inspect=9229", "index.js"]
