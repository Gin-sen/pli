FROM node:15

WORKDIR /usr/src/app/front

COPY apps/front/package.json .
COPY apps/front/package-lock.json .

RUN npm install -g @angular/cli @angular-devkit/build-angular && npm install

EXPOSE 4200

CMD ["npm", "start"]