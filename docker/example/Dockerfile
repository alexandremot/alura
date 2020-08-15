
FROM node:latest
LABEL maintainer="Alexandre Mota"
ENV PORT=3000
COPY . /var/www
WORKDIR /var/www
RUN npm install
ENTRYPOINT npm start
EXPOSE $PORT
