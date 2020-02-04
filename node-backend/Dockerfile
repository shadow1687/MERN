FROM node:10.18.1-alpine3.9
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY package*.json /usr/src/app
COPY . /usr/src/app
RUN npm install -g nodemon

EXPOSE 3000
CMD [ "npm", "start" ]