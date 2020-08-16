FROM node:12.18.3

WORKDIR /usr/src/app

COPY package.json .

RUN yarn global add gatsby-cli

RUN yarn install

COPY . .

CMD ["gatsby", "develop", "-H", "0.0.0.0"]
