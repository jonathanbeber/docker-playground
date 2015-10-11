# Docker Node

## Mounting image

```sh
docker build -t node .
```

## Packages

- Phyton
- NodeJS
  - nodemon

## Running

```sh
docker run -it --rm node <command>
```

If you want to use a local installation of your project, run:

```sh
docker run -it --rm -v $(pwd):/app -p 3000:3000 -p 5858:5858 node <command>
```
