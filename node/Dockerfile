FROM node:current-alpine
COPY . /app
WORKDIR /app
RUN npm install
EXPOSE 80
ENTRYPOINT ["npm", "start"]
