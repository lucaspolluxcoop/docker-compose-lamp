FROM node:14.17-alpine

ENV CONTAINER_PATH /var/www/html

WORKDIR $CONTAINER_PATH

# install nodemon globally
RUN npm install -g nodemon

EXPOSE 3000
EXPOSE 8080

CMD ["nodemon"]
