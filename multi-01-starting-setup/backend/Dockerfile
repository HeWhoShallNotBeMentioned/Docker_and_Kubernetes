FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

CMD ["node", "app.js"]

# to build/run the docker image for the mongobd using the dockerhub mongo image
# docker run --name mongodv -rm -d -p 2701:27017 mongo

# to build the docker image for the backend
# docker build -t goals-node .

# to run the container
# docker run --name goals-backend -rm -d -p 80:80 goals-node

# did not need to create a local image for the mongo file as we used the mongo image from docker hub