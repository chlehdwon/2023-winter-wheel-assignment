# Write client Dockerfile here
# For instructions, see https://github.com/SnowSuno/wheel-assignment-solution#1-dockerfile-%EC%9E%91%EC%84%B1
FROM node:16-alpine

WORKDIR /usr/src/app

COPY . .

RUN npm install && \
    npm install serve -g

RUN npm run build

EXPOSE 80

CMD ["sh", "-c", "serve -s build -l 80"]
