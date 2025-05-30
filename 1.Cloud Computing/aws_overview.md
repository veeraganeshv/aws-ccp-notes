# AWS Overview
## History
- Internally launched in 2002, public launch in America in 2004 with SQS (Simple Queue Service) service, then relaunched with many services SQS, S3 & EC2 in 2006, then launched in Europe in 2007.
- Companies like Dropbox, Netflix, and others started using AWS Cloud services.
- AWS is a major cloud services player in the market with more than 31% share. It has more than 1M active users. (Microsoft Azure is the 2nd player with 25% share)
## AWS Use Cases
- Can build and release sophisticated, scalable applications.
- Can be used in a diverse set of industries.
- used in enterprise IT, Backup and storage, Data analytics, web hosting, backend for mobile and social apps, and building and deploying scalable gaming servers for millions of users.

## AWS Global Infrastructures
- Can be found in infrastructure.aws
### AWS Regions
- It is a Cluster of data centers. It is present all around the world.
- Names can be us-east-1, ap-south-2.
- Most AWS services are region-scoped. ( That means if we use one service in one region, then if we use the same service in another region, it is using a new service for that particular region.)
### How to Choose an AWS Region ( Very Important )  
 - Compliance ( for data security and govt regulations, data never leaves the region without explicit permission )
 - Proximity ( for reduced latency )
 - Availability of Services ( New services might not be available in every region )
 - Pricing ( Different pricing for different regions )
### AWS Availability Zones
 - Minimum 3 availability zones, max 6 can be present in a region.
   - ap-southeast-2a, ap-southeast-2b, ap-southeast-2c
 - Each AZ is one or more discrete data centers with redundant power, network and connectivity
 - They are isolated from each other, so that if one goes down due to a disaster, the other works as expected.
 - All AZs are connected with high bandwidth, low latency connections, all together forming a region.

### AWS Edge Locations/Point of Presence
- AWS has more than 400+ POPs and 10+ regional caches all over the world.
- Content delivery to the user is achieved with lower latency.
  
## Security
 - AWS Infrastructure is secured all around the world. The Follow a Shared Responsibility model applies to the security of all AWS Services.

