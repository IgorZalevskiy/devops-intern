FROM node:latest

WORKDIR /app

COPY package*.json ./

RUN npm install --save

COPY src /app

EXPOSE 4000
CMD ["npm", "start"]