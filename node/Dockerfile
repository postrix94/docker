FROM node

WORKDIR /var/www/html

RUN npm i nodemon

COPY ./ ./

CMD ["nodemon", "app.js --watch"]
