FROM node:alpine

WORKDIR /app

RUN npm install -g create-react-app

COPY ./frontend /app/frontend

WORKDIR /app/frontend/

CMD  sh -c "cd frontend && yarn start"








