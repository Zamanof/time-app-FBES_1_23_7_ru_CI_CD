FROM node:alpine

WORKDIR /app

EXPOSE 5001

COPY package*.json .

RUN npm install

COPY . .

CMD ["npm", "run", "dev"]