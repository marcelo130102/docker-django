# Docker DJANGO

## create build

```bash
docker build . -t linder3hs/docker-django-test
```

## run container

```bash
docker run -p 8000:8000 linder3hs/docker-django-test
```

## run container in background

```bash
docker run -d -p 8000:8000 linder3hs/docker-django-test
```
