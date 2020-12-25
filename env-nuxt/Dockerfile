FROM node:15.5.0-alpine3.10
EXPOSE 80

WORKDIR /home/node/kogoto
COPY package.json /home/node/kogoto/package.json
RUN yarn add nuxt

#dev
COPY kogoto/ /home/node/kogoto/
