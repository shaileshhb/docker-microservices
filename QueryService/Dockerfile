# FROM node:alpine
# WORKDIR /home/app
# COPY . /home/app/
# RUN npm install
# CMD ["npm","start"]


FROM node:alpine

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

CMD [ "npm", "start" ]