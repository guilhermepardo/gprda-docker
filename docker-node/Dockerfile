FROM node:alpine

WORKDIR C:\Users\\Guilherme\\Desktop

COPY package*.json ./

RUN npm install

COPY . . 

EXPOSE 3000

CMD ["npm", "start"]