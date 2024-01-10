FROM node:14
WORKDIR /usr/src/calc
COPY package*.json ./
RUN npm install prettier -g
RUN npm install
COPY . .
RUN npm run build
EXPOSE 3000
CMD [ "node", "start", "index.js" ]
