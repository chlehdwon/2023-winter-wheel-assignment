# Write server Dockerfile here
# For instructions, see https://github.com/SnowSuno/wheel-assignment-solution#1-dockerfile-%EC%9E%91%EC%84%B1
FROM node:16-alpine

WORKDIR /usr/src/app

COPY . .

RUN npm install

EXPOSE 80

LABEL org.opencontainers.image.source https://github.com/chlehdwon/2023-winter-wheel-assignment

CMD ["npm", "run", "serve"]
