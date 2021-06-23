FROM node:alpine

ENV CI=true

WORKDIR /app

COPY package.json /app/

RUN npm install

COPY ./ /app/

CMD ["npm", "start"]