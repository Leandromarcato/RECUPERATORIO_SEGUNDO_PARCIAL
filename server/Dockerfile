FROM node:14-alpine

WORKDIR /servidor

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 5000

CMD ["npm", "start"]
