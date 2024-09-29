FROM node:20

WORKDIR /usr/src/app/my-angular-app

RUN npm install -g @angular/cli

COPY my-angular-app/package*.json ./

RUN npm install --legacy-peer-deps

COPY my-angular-app/ ./

CMD ["npm", "start"]
