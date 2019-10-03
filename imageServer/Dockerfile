FROM node:10-alpine

ADD ImageServer /opt
WORKDIR /opt
RUN npm install
CMD node imageserver.js
EXPOSE 4002
