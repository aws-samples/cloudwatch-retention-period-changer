## Change Cloud Watch Retention Automatically

This Solution will change *ALL* of your CloudWatch Log groups in the chosen reason to your chosen retention period. This is to reduce wasted storage of old logs and to save money. 

### Deployment
Deploy using AWS CloudFormation using the file CloudWatchRetentionPeriodChanger.yaml

### Variables
|Variable| Description | Options| Default|
|--- |--- |--- |--- |
|RetentionDays | What retention in days to set for your group | 1, 3, 5, 7, 14, 30, 60, 90, 120, 150, 180, 365, 400, 545, 731, 1827, 3653 |30|
|RegionToScan | What region to scan and make changed too | AWS regions |us-east-1|

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

