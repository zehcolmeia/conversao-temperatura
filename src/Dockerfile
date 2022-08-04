#mesma versao do node da minha maquina
FROM node:16.14.0

WORKDIR /appZeh

COPY ./package*.json ./

RUN npm install

COPY . . 

EXPOSE 8080

CMD ["node","server.js"]

