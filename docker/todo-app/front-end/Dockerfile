FROM node:16-alpine AS build

WORKDIR /todo-list-app/frontend
ADD ./node_modules.tar.gz ./
COPY . .
EXPOSE 3000
CMD ["npm", "start"]
