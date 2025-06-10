FROM node:24.1.0-alpine
RUN mkdir -p /usr/src/app/server
WORKDIR /usr/src/app/server
COPY package*.json ./
RUN npm install 
COPY . .
EXPOSE 5000
CMD ["npm", "run", "dev"]


