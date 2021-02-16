FROM node:alpine

WORKDIR /app

RUN npm install -g create-react-app

COPY ./frontend /app/frontend

RUN create-react-app frontend

WORKDIR /app/frontend

CMD sh -c "yarn start"


