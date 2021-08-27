FROM node:14.17.5-alpine3.14

WORKDIR /users-service

COPY package.json /users-service/package.json

RUN yarn install

EXPOSE 7101

CMD yarn db:migrate && yarn watch