FROM node:slim

RUN apt-get update
RUN apt-get install -y g++ make apt-utils bzip2 ruby perl python
RUN npm install npm -g
RUN npm install node-pre-gyp -g
RUN npm install node-gyp -g
RUN npm install python -g
RUN npm install express -g
RUN npm install pm2 -g
RUN apt-get -y autoclean
RUN apt-get -y clean
RUN apt-get -y autoremove
EXPOSE 3000
