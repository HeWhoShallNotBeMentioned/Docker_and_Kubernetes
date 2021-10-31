FROM node:16

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]

# build image
# docker build -t goals-react .

# run goals-react container
# docker run --name goals-frontend --rm -p 3000:3000 -it goals-react

# create network
# docker network create goals

# restart 3 containers without the ports being published. They can but not necessary.
# mongodb image create/run
# docker run --name mongodb --rm -d --network goals-net mongo
# express backend
# docker run --name goals-backend --rm -d --network goals-net goals-node

# frontend swap out localhost to the backend server for the running container name


