FROM node:16-alpine

WORKDIR /app

COPY app/ /app/

RUN npm install --production

EXPOSE 3000

CMD ["npm", "start"]
