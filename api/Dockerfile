FROM node:16-alpine

RUN npm install -g nodemon

WORKDIR /app

COPY package.json .

RUN npm install
RUN npm install axios

COPY . .

EXPOSE 4000

CMD ["npm", "run", "dev"]