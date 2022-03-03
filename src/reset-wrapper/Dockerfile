FROM node:16

WORKDIR /app

COPY package.json .
COPY .npmrc .

RUN npm i --save-dev

COPY . .

EXPOSE 4000

ENV REST_ENDPOINT ""

CMD ["npm", "run", "start"]