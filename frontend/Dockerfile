FROM node:alpine
WORKDIR /frontend
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
# CMD [ "node", "server.js" ]
CMD [ "npm", "run", "dev" ]