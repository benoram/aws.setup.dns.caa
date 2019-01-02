# cfn-dns-caa
CloudFormation script caa records for a given Route53 Zone. The template supplies default CAA records to support AWS Certificate Manager (ACM)

Reference: https://en.wikipedia.org/wiki/DNS_Certification_Authority_Authorization

## Parameters

### ZoneId
The Route53 Zone to write CAA records to

### DomainName
The domain name for the zone
