FROM node:16

WORKDIR /todo-list-react-hooks-master/todo-list-react-hooks-master/src/App

COPY . .

RUN npm i
RUN npm install -g serve
RUN npm run build

EXPOSE 3000
ENTRYPOINT ["serve", "-s", "build "]

