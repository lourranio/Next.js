## Building our image

`docker build -t react-app:latest .`


## Running our container

` docker run --name react-app -d -p 3000:3000 react-app:latest `

* -d: This runs your container in detached mode. Simply put, when you leave a terminal session, it keeps your container running still.

* -p: This is used to publish the port you would like your application to run on. If you run your container without publishing a port, whatever is running in your container will only be accessible in your container.

`docker images`
```
REPOSITORY                    TAG       IMAGE ID       CREATED              SIZE
react-app                     latest    250263ebe72e   About a minute ago   1.65GB
```

Abra o browser : http://localhost:3000/


Fonte: https://medium.com/geekculture/getting-started-with-docker-in-your-react-js-application-the-basics-6e5300cf749d