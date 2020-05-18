FROM ubuntu:16.04
WORKDIR /app
COPY kurssitiedot2 .
RUN apt-get update && apt install -y curl && curl -sL https://deb.nodesource.com/setup_10.x | bash && apt install -y nodejs
RUN npm install
CMD npm start

