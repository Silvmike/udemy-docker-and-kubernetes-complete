FROM node:6-alpine

WORKDIR app

COPY package.json ./
RUN npm install
COPY . .

CMD ["npm", "start"]
