FROM node:20
WORKDIR /usr/src/app

COPY package.json package.json
COPY package-lock.json package-lock.json
RUN npm ci

COPY src/. src/.

EXPOSE 33321
CMD [ "npm", "start" ]