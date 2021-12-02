FROM node:14-alpine
WORKDIR /docker/todo-app/front-end
ADD node_modules.tar.gz ./
EXPOSE 3000
COPY . .
ENV REACT_APP_API_HOST localhost
ENV REACT_APP_API_PORT 3001
CMD [ "npm", "start" ] 