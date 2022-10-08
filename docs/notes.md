# learning Docker
This is working through how to use docker and docker-compose.  The point is to start
to use this tooling to introduce docker into our development workflow. The hope is that it
will stream line how we are developing application and moving them between development, testing,
and deployment stages of the development lifecycle.  

run with just docker  
```docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app 1ed199163257126b ```
