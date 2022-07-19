# Basics

Run a container

```dockerfile
docker run [OPTIONS] IMAGE [COMMAND] [ARG...]

--name		// Assign a name to the container

docker run hello-world
```

List containers

```
docker ps [OPTIONS]

-a 			// Show all containers
-f			// filter
-s 			// Display total file sizes
```

Rename

```
docker rename CONTAINER NEW_NAME
// example 
docker rename my_container my_new_container
```

