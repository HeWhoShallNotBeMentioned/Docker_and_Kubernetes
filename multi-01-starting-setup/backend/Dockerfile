FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=chris
ENV MONGODB_PASSWORD=password

CMD ["npm", "start"]

# to build/run the docker image for the mongobd using the dockerhub mongo image
# docker run --name mongodb --rm -d --network goals-net mongo

# to build the docker image for the backend
# docker build -t goals-node .

# to run the container
# docker run --name goals-backend --rm -d -p 80:80 goals-node

# did not need to create a local image for the mongo file as we used the mongo image from docker hub