FROM node:16.18

ENV PORT=3001

COPY . /Simple-Flask-React-App

WORKDIR /simple-flask-react-app

RUN npm install

EXPOSE ${PORT}

CMD ["npm", "start"]