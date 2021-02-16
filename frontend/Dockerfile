FROM node:alpine

RUN mkdir /frontend 

WORKDIR /frontend

RUN npm install -g create-react-app


COPY ./frontend /frontend

RUN create-react-app frontend

WORKDIR /frontend

CMD sh -c "yarn start"


