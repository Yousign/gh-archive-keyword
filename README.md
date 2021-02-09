# GH Archive Keyword

You only need `make`, `docker` and `docker-compose` installed to start the development environment.

## Start the development environment

The following command will start the development environment.
You can access to the application at http://127.0.0.1:8000/ :

```bash
make start
```

## Access to a shell in the PHP container

```bash
make shell
```

## Tests tools

You can run PHPUnit with the following command:
```bash
# Run the unit test suite
make unit-test

# Run the functionnal test suite
make func-test
```

## Stop the development environment

You can stop the development environment running this command:
```bash
make stop
```

## Clean the development environment

You can clean the development environment (docker images, vendor, ...) running this command:
```bash
make clean
```

## Makefile targets

You can get available targets by running:
```bash
make
```

```bash
build                          Build the docker stack
pull                           Pulling docker images
shell                          Enter in the PHP container
start                          Start the docker stack
stop                           Stop the docker stack
clean                          Clean the docker stack
vendor                         Install composer dependencies
unit-test                      Run PhpUnit unit testsuite
func-test                      Run PhpUnit functionnal testsuite
```
