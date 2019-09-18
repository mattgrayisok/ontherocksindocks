FROM node:8.16

RUN apt-get update && apt-get install -y apt-transport-https

WORKDIR /project

COPY ./src/frontend .
RUN npm install

CMD npm run build
