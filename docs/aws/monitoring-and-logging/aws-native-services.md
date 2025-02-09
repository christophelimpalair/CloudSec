## Logging Services
The primary security logging services in AWS are:

- [ :octicons-link-external-16: AWS CloudTrail](https://aws.amazon.com/cloudtrail/)
- [ :octicons-link-external-16: Amazon CloudWatch](https://aws.amazon.com/cloudwatch/)
- [ :octicons-link-external-16: VPC Flow Logs](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html)
- [ :octicons-link-external-16: Amazon Route 53 Query](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/logging-monitoring.html)

## Types of logs
There are generally two broad categories of logging:

- Control plane events
- Services logs

Control plane events are events that happen at the management layer, meaning the layer responsible for managing and controlling cloud resources. This could be creating, modifying, or deleting a resource. For example, if someone modifies a security group's rules, that would be considered a control plane event.

Service logs, instead, are more specific logs that are generated by individual services or applications. 

!!! note "Example:" 
    
    If you have AWS Lambda functions executing code and writing logs, those would be considered service logs. If someone goes in and creates a new Lambda function, then that would be a control plane event.

## Log aggregators
The primary security logging aggregators in AWS are:

- [ :octicons-link-external-16: Amazon S3](https://aws.amazon.com/s3/)
- [ :octicons-link-external-16: Amazon Security Lake](https://aws.amazon.com/security-lake/)
- [ :octicons-link-external-16: Amazon Kinesis Data Firehose](https://aws.amazon.com/kinesis/data-firehose/)
- [ :octicons-link-external-16: Amazon Athena](https://aws.amazon.com/athena/)

## Visualization
The primary security visualization services in AWS:

- [ :octicons-link-external-16: Amazon OpenSearch](https://aws.amazon.com/opensearch-service/)
- [ :octicons-link-external-16: Amazon QuickSight](https://aws.amazon.com/quicksight/)
- [ :octicons-link-external-16: Amazon Managed Grafana](https://aws.amazon.com/grafana/)
- [ :octicons-link-external-16: Amazon CloudWatch](https://aws.amazon.com/cloudwatch/) (offers custom dashboards)