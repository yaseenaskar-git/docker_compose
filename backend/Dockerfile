FROM node:18-alpine

WORKDIR /web

COPY package.json .
COPY package-lock.json .

RUN npm install 

COPY . . 

RUN mkdir -p /app/data

EXPOSE 5000

CMD ["npm", "start"] 
