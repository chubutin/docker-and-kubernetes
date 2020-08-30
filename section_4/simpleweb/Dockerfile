# Specify a base image
FROM node:alpine

WORKDIR /usr/app

# Install some dependencies
COPY ./package.json ./
RUN npm install

# Copy project files
COPY ./ ./

# Default command
CMD ["npm", "start"]