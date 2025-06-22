FROM node:24-alpine3.21

COPY server.js /app/server.js
COPY package.json /app/package.json
COPY package-lock.json /app/package-lock.json

EXPOSE 8000

WORKDIR /app
RUN npm install

CMD ["npm", "run", "dev"]