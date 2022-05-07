From node:18-alpine3.14
WORKDIR /app
COPY . .
RUN npm install && npm install -g nodemon
EXPOSE 8000
CMD ["nodemon", "app.js"]