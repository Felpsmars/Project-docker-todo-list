FROM node:14-alpine
WORKDIR /docker/todo-app/back-end
COPY package*.json ./
ADD node_modules.tar.gz ./
COPY . .
EXPOSE 3001
ENTRYPOINT ["npm start"]