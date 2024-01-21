FROM node:latest

RUN npm install -g pm2

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 5001

CMD ["pm2-runtime", "index.js"]
