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
