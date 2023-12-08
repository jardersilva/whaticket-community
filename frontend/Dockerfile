FROM node:16.14.2 as build-deps
WORKDIR /usr/src/app
COPY ./ /usr/src/app/
RUN npm install
RUN npm run build


EXPOSE 80
CMD node server.js
