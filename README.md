# fake-rest-api
This project demonstrates how to create a fake REST API using [json-schema-faker](https://github.com/json-schema-faker/json-schema-faker) and [json-server](https://github.com/typicode/json-server).

See my [blog post](https://medium.com/@jonjam/creating-a-fake-rest-api-with-json-server-817320239cde) for more details.

## Install

Install dependencies with:

```bash
yarn install
```

## Usage

Start the REST API with:

```bash
yarn run start
```

This will generate random data in `/buildScripts/db.json` and then serve it on a REST API on port 3000.

## Related links
* https://medium.freecodecamp.org/rapid-development-via-mock-apis-e559087be066
* https://github.com/coryhouse/mock-api-example
* https://github.com/yeay-tv/fake-rest-api
