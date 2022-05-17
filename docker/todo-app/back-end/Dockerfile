FROM node:16-alpine AS build

WORKDIR /todo-list-app
ADD ./node_modules.tar.gz ./
COPY . .
EXPOSE 3001
CMD ["npm", "start"]
