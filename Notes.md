# Why don't use internet
* Latency
* Consistent
* Bandwidth cost reduction
* Compliance & trust


# Types of interfaces
Public Interface
-- examples: S3, Dynamo, RDS, anything with an amazon dns
Private peering (Only one partner allows this for GovCloud)
-- example: VPC, EC2

Direct Connect Gateway acts as a transit VPCs to a commercial AWS account (which allows you use multiple partners)

You can use the transit VPC to direct traffic over both the DC and the Internet.  This allows diversity and high availability.   