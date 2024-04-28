FROM node:lts
WORKDIR ./app/
COPY ./paginaTV-front/app .
RUN npm install -g @angular/cli
RUN npm install
CMD ["ng", "serve", "--host", "0.0.0.0"]
