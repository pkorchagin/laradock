FROM node:10

WORKDIR /usr/src/app/react

COPY package*.json ./

RUN npm install node-sass && npm install

EXPOSE 3007

CMD ["npm", "start"]
