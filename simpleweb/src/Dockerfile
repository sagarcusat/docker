FROM node:alpine

WORKDIR /usr/app

COPY package.json ./

RUN npm install

COPY ../../src/simpleweb ./

RUN ["npm", "start"]

