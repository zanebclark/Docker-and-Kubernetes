# Specify a base image
FROM node:alpine

WORKDIR /usr/app

# Install some dependendencies
COPY . .

COPY ./package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]