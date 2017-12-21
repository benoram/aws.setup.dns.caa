# DNS CAA Record Setup
Setup CAA records on zone

## Prerequisites
[AWS CLI](http://docs.aws.amazon.com/rekognition/latest/dg/setup-awscli.html)

## Setup
Run in console and set params AdHoc, or add required parameters to CLI script as appropriate for your domain

```
aws cloudformation create-stack --stack-name aPrimaryDNSCAARecords --template-body file://./cfn-dns-caarecords.yaml
```
