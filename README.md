# Aiplus Docker


## Pre settings

### Clone project
```bash
# Clone
git clone git@github.com:pipisasa/aiplus-docker.git

# Open project
cd aiplus-docker
```

### Cloning repositories

<br/>

#### Clone [Backend](https://github.com/pipisasa/aiplus-nestjs/)

```bash
# Clone Backend
git clone git@github.com:pipisasa/aiplus-nestjs.git backend


# Checkout to docker branch
cd backend
git checkout -b docker origin/docker
cd ..
```

<br/>

#### Clone [Frontend](https://github.com/pipisasa/aiplus-blitz)

```bash
# Clone Backend
git clone git@github.com:pipisasa/aiplus-blitz.git frontend

# Checkout to docker branch
cd frontend
git checkout -b docker origin/docker
cd ..
```

## Docker Compose
```bash
docker-compose up
```
