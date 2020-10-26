#specify a base image
FROM node:alpine

ENV CI=true

WORKDIR /app

#install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

#Default command
CMD ["npm", "start"]