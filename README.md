
# AWS Node Project

This is a basic product for running serverless functions locally using serverless-offiline and docker

## Usage

### Installing

```bash
$ npm i
```
```bash
$ docker-compose build
```

### Running

```bash
$ docker-compose up
```

### Invocation

After successful inslalling, you can invoke the function by using the following command:

```bash
serverless invoke local --function ping
```

Which should result in response similar to the following:

```json
{
    "statusCode": 200,
    "body": "{\"message\": \"pong\"}"
}
```