# Tests with Pest PHP

Tests with Pest PHP using a Docker.

- PHP: 8.1.10 (cli)
- Pest PHP: 1.22

## Run tests

```sh
$ docker run --rm -v $(pwd):/app -w /app php:8.1.10-cli-alpine3.16 php ./vendor/bin/pest
```

---

Composer

```sh
$ docker run --rm --interactive --tty --volume $PWD:/app composer <command>
```
