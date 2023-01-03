# Docker DJANGO

## create build

```bash
docker build . -t django-app
```

## run container

```bash
docker run -p 8000:8000 django-app
```

## run container in background

```bash
docker run -d -p 8000:8000 django-app
```
