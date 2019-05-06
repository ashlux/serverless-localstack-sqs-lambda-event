# serverless-localstack-sqs-lambda-event

Example project to reproduce an issue with LocalStack and Serverless. See: https://github.com/localstack/localstack/issues/1288.

Deploying to [LocalStack](https://github.com/localstack/localstack):

```
docker-compose up -d

serverless deploy --stage local
```

Deploying to AWS:

```
serverless deploy
```
