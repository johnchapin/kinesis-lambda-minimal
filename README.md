# kinesis-lambda-minimal

The minimum classes and dependencies required for a Lambda to process Kinesis events.

### Kinesis Lambda Minimal v1.0.0 includes:

 - `com.amazonaws.services.kinesis.model.Record` (cf8422a) from [Kinesis Java SDK v1.11.21](https://github.com/aws/aws-sdk-java/tree/1.11.21/aws-java-sdk-kinesis)
 - `com.amazonaws.lambda.runtime.events.KinesisEvent` (5f54d74) from [Lambda Java Events v1.3.0](https://github.com/aws/aws-lambda-java-libs/tree/65ef84f630638a149fab6504d938d234eef0da4a/aws-lambda-java-events)
 - `com.amazonaws.services.kinesis.clientlibrary.types.Messages` (4dfc17d) from [Kinesis Client Library v1.6.5](https://github.com/awslabs/amazon-kinesis-client/tree/v1.6.5)
 - `com.amazonaws.services.kinesis.clientlibrary.types.UserRecord` (c6e393c) from [Kinesis Client Library v1.6.5](https://github.com/awslabs/amazon-kinesis-client/tree/v1.6.5)
  - Usage of commons-lang (specifically `StringUtils`) has been removed
  - Usage of commons-logging has been replaced with `java.util.logging`

