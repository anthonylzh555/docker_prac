# Specify a Base Image
FROM node:alpine

WORKDIR /usr/app

# Install some dependancies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm","start"]