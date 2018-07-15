# App

## Prepare Environment

```bash
linux:~/hello # pip install -r requirements.txt
```

## Run App

```bash
linux:~/hello # python app.py
```

## Test App

```bash
linux:~/hello # curl http://127.0.0.1:8080
```


---

# Docker

## Build Image

```bash
linux:~/hello # docker build -t hello .
```

## Run Container

```bash
linux:~/hello # docker run -itd -p8080:8080 --name hello hello
```

## Stop Container

```bash
linux:~/hello # docker stop hello
```


---

# Docker Compose

## Run App
 
```bash
linux:~/hello # docker-compose up -d
```

## Stop App

```bash
linux:~/hello # docker-compose stop
```
