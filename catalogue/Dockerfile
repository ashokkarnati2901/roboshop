FROM node:14

EXPOSE 8080

WORKDIR /opt/server

COPY package.json /opt/server/

#npm will install the dependenices required for node js project
RUN npm install

COPY server.js /opt/server/

ENTRYPOINT ["node", "server.js"]

