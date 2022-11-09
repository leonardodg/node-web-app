# Project Example NodeJS run on Docker with server in Express

Create Web App Example - NodeJS (Express) And Docker 


- Run in docker cli
```
$ docker build . -t name-test/node-web-app

$ docker run -p 8080:8080 -d name-test/node-web-app
```

- Run in Docker Compose
```
$ docker-compose up -d --build
```

- Docs Example in Node.org
[Link](https://nodejs.org/en/docs/guides/nodejs-docker-webapp)
