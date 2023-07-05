FROM --platform=linux/amd64 node:16-slim

WORKDIR /app

COPY . .

RUN npm install

EXPOSE 8080

CMD ["node", "index.js"]