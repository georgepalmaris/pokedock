FROM node:latest as builder

WORKDIR '/app'

COPY package.json .

RUN npm install --production

COPY . .

RUN npm start