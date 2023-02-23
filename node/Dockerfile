FROM node:18-alpine
RUN apk add git openssh
WORKDIR /app
COPY package*.json yarn.lock ./
RUN yarn install --network-timeout=600000