FROM node:14

WORKDIR /simple-web-server

COPY . .

RUN yarn install --production

EXPOSE 4000

CMD ["node", "src/app.js"]
