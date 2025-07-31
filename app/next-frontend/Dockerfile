FROM node:latest

WORKDIR /app/next-frontend

RUN apt-get update 

COPY ./ /app/

RUN npm install

CMD ["npm", "run", "dev"]
