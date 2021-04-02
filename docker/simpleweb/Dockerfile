# Specify a base image
FROM node:current-buster-slim

WORKDIR /usr/app

#Install some dependecies
COPY ./ ./
RUN npm install 

#Default command
CMD ["npm", "start"]