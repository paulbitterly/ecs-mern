FROM node:14-alpine

WORKDIR /app

COPY package.json .

RUN npm install

COPY ./site-assets/ .

EXPOSE 80

CMD ["node", "app.js"]