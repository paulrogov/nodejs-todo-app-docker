# Todo App Docker
If you want to embed images, this is how you do it:  

<!--![Demo](todo-list-sample.png)-->
<img src="todo-list-sample.png" alt="drawing" height="400" />

## Commands  
**Build image from Dockerfile**
```
docker build -t getting-started-nodejs .
```

**Run container**
```
docker run -dp 3000:3000 getting-started-nodejs
```

**Execute commands inside a container**
```
docker exec -it <container_id> /bin/sh
```

Tutorial:  
https://docs.docker.com/get-started/02_our_app/  