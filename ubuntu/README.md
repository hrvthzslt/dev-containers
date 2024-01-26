# Ubuntu dev container

## Fast start

run `./setup` to start the container.

## Build and run

```bash
docker build -t ubuntu-ssh .
docker run -d -p 2222:22 --name ubuntu-ssh ubuntu-ssh
```

## Connect trough SSH

```bash
ssh -p 2222 user@localhost
```

Password is... well `password`.
