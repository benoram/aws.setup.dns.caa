# DNS CAA Record Setup
Setup CAA records on zone

## Prerequisites
[AWS CLI](https://docs.aws.amazon.com/cli/latest/reference/)

## Setup

```
TEMP_DOMAINNAME='Domain.com'
TEMP_ZONE_ID='ZQ12345'

aws cloudformation create-stack --stack-name aPrimaryDNSCAARecords --template-body file://./cfn-dns-caarecords.yaml --region us-east-1  --parameters ParameterKey=Domain,ParameterValue=$TEMP_DOMAINNAME ParameterKey=ZoneId,ParameterValue=$TEMP_ZONE_ID
```
