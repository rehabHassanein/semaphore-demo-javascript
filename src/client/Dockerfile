FROM node:8.9

RUN mkdir /var/app

WORKDIR /var/app

ADD . .

RUN npm install

EXPOSE 3000

CMD ["npm","run","start"]
