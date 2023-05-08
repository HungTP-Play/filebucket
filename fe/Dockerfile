FROM node:18.16-alpine3.16

WORKDIR /app

COPY . .

RUN rm -rf node_modules && rm -rf package-lock.json && npm install

RUN npm run build

CMD ["npm", "run", "start"]