FROM node:alpine as builder

WORKDIR /usr/src/app
COPY package.json ./

RUN npm install 
RUN npm install react-scripts@4.0.3 -g

COPY ./ ./

EXPOSE 3000
CMD ["npm","run","start"]
