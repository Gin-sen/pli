FROM node:15

WORKDIR /usr/src/app/api

COPY apps/back/package*.json ./

RUN npm install && npm fund
EXPOSE 3000

#CMD ["ls", "-al"]
CMD ["node", "server.js"]
USER node
