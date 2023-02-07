FROM node:latest

COPY package.json server.js /

RUN npm install

EXPOSE 3000

COPY . .

CMD [ "node", "server.js" ]