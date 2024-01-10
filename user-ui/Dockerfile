FROM node:14
WORKDIR /usr/src/calc
COPY package*.json ./
run npm install prettier -g
RUN npm install
COPY . .
RUN npm run build
EXPOSE 3000
CMD [ "node", "start", "index.js" ]
