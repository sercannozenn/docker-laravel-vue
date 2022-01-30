FROM node:lts-alpine

WORKDIR /var/www/html/proje

COPY package*.json ./

RUN npm install


CMD ["npm", "run", "build"]