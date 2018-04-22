# HTTPie in Docker

## Description

Docker image for HTTPie. For your convenience to run!

## Usage

On a machine with Docker, run the following commmand:

```shell
docker run --rm nomaster/httpie GET https://example.com
```

Maybe even more convenient: set a shell alias!

```
alias http="docker run --rm nomaster/httpie"
http GET https://example.com
```

## Further information

See the [HTTPie documentation](https://httpie.org/doc).
