FROM node:16-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install && \

    npm cache clean --force

COPY . .

EXPOSE 5000

CMD ["npm", "start"]

