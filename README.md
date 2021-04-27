## Commitsar

To run commitsar use this shell command:

```shell
docker run --rm --name="commitsar" -w /src -v "$(pwd)":/src aevea/commitsar commitsar .
```