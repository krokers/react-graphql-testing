FROM node:15

#where the app lives within the container
WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 4040

CMD ["npm","start"]

