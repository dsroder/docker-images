# Base Image
FROM node:alpine

WORKDIR /usr/app

# Dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default CMD
CMD ["npm", "start"]