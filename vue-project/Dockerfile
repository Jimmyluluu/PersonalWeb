FROM node:16.18-slim

COPY . /vue-project

WORKDIR /vue-project

RUN npm install

EXPOSE 5173

CMD ["npm", "run", "dev"]