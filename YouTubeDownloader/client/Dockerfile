FROM node:12.16.1 as install

WORKDIR /app

COPY package*.json ./

RUN npm ci 

COPY . .

RUN npm run build

#CMD ["npm","start"]


