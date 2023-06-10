FROM node:16

WORKDIR /usr/src/app

EXPOSE 5001

COPY ./example-frontend/ /usr/src/app/

RUN npm install
RUN npm run build
RUN npm install -g serve

CMD serve -s -l 5001 build