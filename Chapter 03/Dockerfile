FROM node:24.4.1-alpine3.21
EXPOSE 3000
WORKDIR /app
COPY package.json index.js ./
RUN npm install
CMD ["npm", "start"]
