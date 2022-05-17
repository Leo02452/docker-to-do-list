FROM mjgargani/puppeteer:trybe1.0 AS build

WORKDIR /todo-list-app/tests
ADD ./node_modules.tar.gz ./
COPY . .
CMD ["npm", "test"]
