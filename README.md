# simple-express
This is a simple node-express project for testing environment on vps hosting hostinger with docker

## How to install locally

```
git clone https://github.com/ussho-dev/simple-express.git
cd simple-express
npm install
```

## How to run locally

```npm start``` or ```node server.js```

Then access http://localhost:3000

## How to run with docker

```
docker build . -t simple-express
docker run -p 3000:3000 simple-express
```

Then access http://localhost:3000
