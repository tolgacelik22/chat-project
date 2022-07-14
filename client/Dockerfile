FROM node:16-alpine3.12
WORKDIR /client/
COPY . /client/

RUN npm install

EXPOSE 8080
CMD ["npm", "run", "serve"]