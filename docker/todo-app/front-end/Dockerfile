FROM node:14-alpine

WORKDIR /front-end

ADD node_modules.tar.gz .

COPY . .

RUN npm install

ENTRYPOINT ["npm", "start"]

EXPOSE 3000
