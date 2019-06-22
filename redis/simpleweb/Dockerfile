FROM alpine
RUN apk add --update nodejs
RUN apk add --update nodejs-npm

WORKDIR /user/app

COPY ./ ./
RUN npm install

CMD ["npm", "start"]
