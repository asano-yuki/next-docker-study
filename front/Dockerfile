FROM node:16.17
COPY . /usr/src/app
ENV CHOKIDAR_USEPOLLING=true
WORKDIR /usr/src/app
CMD yarn install && yarn dev