FROM node:20.18.3-alpine3.21
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]