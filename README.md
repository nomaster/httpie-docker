# HTTPie in Docker

## Description

Docker image for HTTPie. For your convenience to run!

## Usage

On a machine with Docker, run the following commmand:

```shell
docker run --rm -t nomaster/httpie GET https://example.com
```

Maybe even more convenient: set a shell alias!

```
alias http="docker run --rm -t nomaster/httpie"
http GET https://example.com
```

## Further information

For examples and usage, see the [man page](https://www.mankier.com/1/http).

Also see the [HTTPie documentation](https://httpie.org/doc) for a complete reference.

## Credits

HTTPie by [Jakub Roztočil](https://github.com/jakubroztocil/httpie).
