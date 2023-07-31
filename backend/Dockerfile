FROM node:13.12.0-alpine3.11

WORKDIR /backend

COPY package*.json ./

RUN npm install

COPY . ./

EXPOSE 5000

CMD ["npm", "start"]