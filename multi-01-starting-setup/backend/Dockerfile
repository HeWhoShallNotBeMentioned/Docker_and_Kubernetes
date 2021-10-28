FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

CMD ["node", "app.js"]

# to build the docker image
# docker build -t goals-node .

# to run the container
# docker run --name goals-backend -rm -d -p 80:80 goals-node