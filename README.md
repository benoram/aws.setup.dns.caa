# DNS CAA Record Setup
Setup CAA records on zone

## Prerequisites
[AWS CLI](http://docs.aws.amazon.com/rekognition/latest/dg/setup-awscli.html)

## Setup

```
aws cloudformation create-stack --stack-name aPrimaryDNSCAARecords --template-body file://./cfn-dns-caarecords.yaml --region us-east-1
```
