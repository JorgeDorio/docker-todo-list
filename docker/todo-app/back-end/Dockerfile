FROM node:14-alpine

WORKDIR /back-end

ADD node_modules.tar.gz .

COPY . .

RUN npm install

ENTRYPOINT ["npm", "start"]

EXPOSE 3001
