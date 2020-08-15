
FROM node:latest
MAINTAINER Alexandre Mota
COPY . /var/wwww
WORKDIR /var/www
RUN npm install
ENTRYPOINT ["npm", "start"]
EXPOSE 3000
