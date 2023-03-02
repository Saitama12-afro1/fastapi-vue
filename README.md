
Build the images and spin up the containers:

```sh
$ docker-compose up -d --build
```

Apply the migrations:

```sh
$ docker-compose exec backend aerich upgrade
```
