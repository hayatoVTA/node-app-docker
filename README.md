# node-app-docker

- build
```
$ docker build -t [imageタグ名] .
```

- run
```
$ docker run -p 3000:3000 -d --name [コンテナタグ名] [既存のimageタグ名] .
```
