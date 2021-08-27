FROM node:14.17.5-alpine3.14

WORKDIR /chat-app

COPY package.json /chat-app/package.json

RUN yarn install

EXPOSE 7001

CMD ["yarn", "watch"]