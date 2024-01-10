FROM node:17
WORKDIR /usr/src/calc
COPY package*.json ./
RUN npm install
COPY . . 
RUN npm run build
EXPOSE 3000
CMD [ "node", "src/index.js" ]
