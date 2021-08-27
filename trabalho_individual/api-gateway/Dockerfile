FROM node:14.17.5-alpine3.14

WORKDIR /api-gateway

COPY package.json /api-gateway/package.json

RUN yarn install

EXPOSE 7000

CMD ["yarn", "watch"]