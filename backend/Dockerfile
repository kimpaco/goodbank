FROM node:slim

WORKDIR /server

COPY package.json ./

RUN npm install

COPY . .


EXPOSE 3000
CMD ["node", "index.js"]