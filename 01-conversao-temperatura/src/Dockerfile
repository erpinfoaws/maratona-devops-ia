# criar um dockerfile para criar uma imagem do nodejs
FROM node:18
workdir /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
