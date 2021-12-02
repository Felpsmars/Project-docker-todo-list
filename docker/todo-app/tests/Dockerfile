FROM mjgargani/puppeteer:trybe1.0
WORKDIR /docker/todo-app/tests
ADD node_modules.tar.gz ./
COPY . .
ENV FRONT_PORT 3000
ENV FRONT_HOST localhost
CMD [ "npm", "test" ] 