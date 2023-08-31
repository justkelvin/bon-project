FROM node:14

WORKDIR /bon-api
COPY package.json .
RUN npm install
COPY . .
CMD npm start
