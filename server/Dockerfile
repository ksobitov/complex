FROM node:18.14-alpine
WORKDIR /usr/src/app
COPY package.json .
RUN npm i
COPY . .
CMD ["npm", "start"]
