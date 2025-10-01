FROM node:22.20.0-alpine

WORKDIR /app

COPY package.json package-lock.json /app/

RUN npm install --ignore-scripts

COPY . /app/

EXPOSE 3008

CMD ["node", "index.js"]
