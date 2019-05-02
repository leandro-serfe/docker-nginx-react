# Stage 1 - the build process
FROM node:10.15.3-alpine as build-deps
WORKDIR /usr/src/app

COPY . ./
RUN yarn install

## uncomment below for stage environment
#RUN yarn build
#comment below for stage environment
EXPOSE 3000
