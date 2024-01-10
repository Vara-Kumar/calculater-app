FROM node:17
WORKDIR /usr/src/calc
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD [ "node", "src/App.js" ]
