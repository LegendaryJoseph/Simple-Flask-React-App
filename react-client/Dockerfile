FROM node:22-alpine3.19

COPY . /react-client

WORKDIR /react-client

RUN npm install

EXPOSE ${PORT}

CMD ["npm", "start", "--port=3000"]