## dotnet run redis example

### How to install redis

```shell
#install redis image
docker build -f Dockerfile ..
```

```shell
#run redis
docker run -d --name redisDev -p 6379:6379 redis
```

### Use Package

```shell
dotnet add package ServiceStack.Redis
```