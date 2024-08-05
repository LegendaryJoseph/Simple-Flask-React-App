FROM node:16.18

COPY . /react-client

WORKDIR /react-client

RUN npm install

EXPOSE ${PORT}

CMD ["npm", "start", "--port=3000"]