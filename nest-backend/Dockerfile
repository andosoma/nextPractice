FROM node:latest

WORKDIR /app/nest-backend

COPY ./ /app/
RUN npm install
RUN npm run build
CMD ["npm", "run", "start"]