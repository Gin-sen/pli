FROM node:15

WORKDIR /usr/src/app/front

COPY apps/front/package.json .
COPY apps/front/package-lock.json .

#RUN npm install -g @angular/cli && npm install
RUN npm install -g @angular/cli @angular-devkit/build-angular && npm install
RUN npm fund
#RUN npm audit fix
#RUN npm audit fix --force
EXPOSE 4200

CMD ["npm", "start"]