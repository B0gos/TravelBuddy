FROM node:latest

WORKDIR /root/
ADD server.js ./
ADD package.json ./

RUN ["npm", "install"]


EXPOSE 3000/tcp
ENTRYPOINT ["node", "server.js"]
