# cloudformation
Misc cloudformation scripts that may be useful to others

## cfn-cert-expiry.yaml

This CloudFormation template sets up a Lambda function run on a schedule which monitors ACM for certificate expiry dates at regular intervals and sends an SNS notification when something is about to expire.

This is extremely useful if you have imported certificates that are not automatically renewed by ACM and you need to know if they are about to expire in good time so that replacements can be organised.

Please leave a comment if you find any of these scripts useful.
