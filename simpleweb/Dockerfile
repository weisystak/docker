# Specify a base image
FROM node:alpine

WORKDIR /usr/kkk

# Install some depenendencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "start"]