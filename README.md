# Docker PHP Boilerplate

* Please add api.boilerplate.develop to your etc/hosts

* got to the root of the project and execute on /nginx_proxy/:
```$bash
docker-compose up -d
```

this will initialize the nginx-proxy in order to have multiple projects
running on the port 80.

* Go back to the root and execute:
```$bash
docker-compose build

docker-compose up -d
```

* Install via composer any framework you want inside the container and start working.

* Comment out on the docker file line 85 to 87 and 112.

