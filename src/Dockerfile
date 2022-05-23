FROM node:16
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install -g npm@8.10.0
COPY . .
EXPOSE 3000
CMD ["node", "serverexample.js"]
