FROM node:10-alpine

ADD PdfServer /opt
WORKDIR /opt
RUN npm install
CMD node pdfserver.js
EXPOSE 4003
