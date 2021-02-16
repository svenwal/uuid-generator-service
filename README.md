# UUID generator service

![CI](https://github.com/aaronhmiller/uuid-generator-service/workflows/CI/badge.svg)

This is a demo OpenAPI / Swagger to generate a UUID using https://httpbin.org

It also has a second endpoint /delay/0-10 which is being auto validated by the request validator plugin (schema is auto-generated based on OpenAPI spec)

It's intended to be used with https://github.com/aaronhmiller/uuid-generator-workspace

There is actually no code at all in this repo - it's the base of an example ci/cd chain
