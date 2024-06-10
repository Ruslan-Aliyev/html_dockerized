# Simple Hello World Static HTML website - Dockerized

```
docker build -t atabegruslan/static:1.0 .
docker run -d -p 8088:80 --name static_example_name atabegruslan/static:1.0
```

![](/Illustrations/build_and_run_locally.png)

Shell into it: `docker exec -it static_example_name bash`

## Push to DockerHub

Create a repo on DockerHub called "static" first

![](/Illustrations/push_to_dockerhub.png)

![](/Illustrations/dockerhub.png)

---

# Tutorials

- https://www.youtube.com/watch?v=K6WER0oI-qs&list=PLoYCgNOIyGAAzevEST2qm2Xbe3aeLFvLc&index=3 
- https://github.com/learncodeacademy/docker-static-nginx
