FROM node:20.20.0-alpine3.23
WORKDIR /opt/backend
COPY package.json .
COPY *.js .
RUN npm install
ENV DB_HOST="mysql"
#ENV DB_HOST="localhost"
CMD [ "node", "index.js" ]