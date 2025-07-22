FROM node:22.17.1-alpine

WORKDIR /app

COPY package.json package-lock.json /app/

RUN npm install --ignore-scripts

COPY . /app/

EXPOSE 3008

CMD ["node", "index.js"]
