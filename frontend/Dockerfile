FROM node:25

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

ENV BROWSER=none

EXPOSE 3000

CMD ["npm","start"]