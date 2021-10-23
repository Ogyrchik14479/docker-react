FROM node:14-alpine3.12

WORKDIR /usr/src/frontend

COPY package*.json ./

RUN npm install

COPY . .
