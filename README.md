# Laravel dev box

## Build image

```bash
$ cd .
$ docker build -t larabox .
```

## How to run

```bash
$ cd laravel-project
$ docker run --rm -it -v $(pwd):/app /bin/bash
```

or
add alias:
`alias larabox='docker run --rm -it -v $(pwd):/app larabox /bin/bash'`
and run:

```
$ cd laravel-project
$ larabox
```
