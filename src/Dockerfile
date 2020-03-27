# docker build

FROM node

RUN mkdir -p /var/app

WORKDIR /var/app

COPY package.json ./

RUN npm install

RUN npm install -g nodemon

EXPOSE 10000

# docker run

CMD ["nodemon", "backend/index.js"]