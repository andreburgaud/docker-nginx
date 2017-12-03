# NGINX Docker Image

Docker image for NGINX, based on Alpine Linux.

# Pull the Image

```
$ docker pull andreburgaud/nginx
```

# Run a Container

```
$ docker run --rm -p 8888:80 andreburgaud/nginx
```

Then, point a browser to http://localhost:8888.

# Stop the Container

If the container was started as described in the section above, simply press `[CTRL+C]` in the terminal the container is attached to. The container will stop after a couple of seconds.

# License

MIT License (see LICENSE file)

This project includes files, `nginx.conf` and `default.conf`, copied from the **Official NGINX Dockerfiles** project: https://github.com/nginxinc/docker-nginx. The files in the **Official NGINX Dockerfiles** project are released under the MIT license.

# Resources

* https://www.nginx.com/
* https://github.com/nginxinc/docker-nginx

