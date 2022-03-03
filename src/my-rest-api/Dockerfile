FROM node:16

WORKDIR /app

COPY package.json .
COPY .npmrc .

RUN npm i --save-dev

COPY . .

EXPOSE 3000

CMD ["npm", "run", "start"]