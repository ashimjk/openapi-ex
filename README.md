# OpenAPI

## Run Generator
```shell
docker run --rm \
    -v $PWD:/local openapitools/openapi-generator-cli generate \
    -i /local/petstore.yaml \
    -g spring \
    -o /local/out/spring
```