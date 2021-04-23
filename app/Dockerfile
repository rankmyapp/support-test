FROM node:lts-alpine

LABEL mantainer="RankMyAPP"
LABEL version="1.0"

WORKDIR /var/www/app

COPY ./ /var/www/app

RUN yarn install

EXPOSE 3001

CMD ["yarn", "start"]
