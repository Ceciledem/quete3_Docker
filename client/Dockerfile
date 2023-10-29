FROM node:lts-alpine

RUN mkdir /app
WORKDIR /app
COPY package*.json ./
RUN npm i
RUN npm install -g nodemon
RUN npm install mongoose

COPY public public
COPY src src

CMD npm start
