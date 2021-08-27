FROM node:14.17.5-alpine3.14

WORKDIR /chat-service

COPY package.json /chat-service/package.json

RUN yarn install

EXPOSE 7100

CMD ["yarn", "watch"]