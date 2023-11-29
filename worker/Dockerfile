FROM node:alpine14.14.0
WORKDIR /usr/src/app
COPY package.json .
RUN npm i
COPY . .
CMD ["npm", "start"]
