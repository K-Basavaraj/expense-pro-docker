# #1st Best Practice implimented bridgenetwork(default)
FROM node:20
EXPOSE 8080
#it become bridge network which container network
ENV DB_HOST="mysql" 
RUN mkdir /opt/server
WORKDIR /opt/server
COPY package.json .
COPY *.js .
RUN npm install 
CMD ["node", "index.js"]