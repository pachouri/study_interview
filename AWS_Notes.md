Virtualazation in AWS: 
<br>Hypervisor: Type1 & Type2
<br> XEN Hypervisor: 
<br> AWS vs Azure vs GCP: Aws has more availability zone, Old, 
<br> GCP is a leader in AI/ML.
<br> EC2: Elastic compute cloud,  Various CPU, Memory, Storage available.
<br> Combination of instance type: 
<br> Intance Type: 1.General Purpose type, 2. Memory Optipmized,3. Storage Optimize, 4: Acceletarted ,5 : compute optimized.
<br> <b> AMI (Amazon Machine Image)></b>
<br> Operating System, Architecture, Storage, Virtualization
<br> Replication previous machine.
<br><b> Regions & Availability Zones:</b>
<br> Region: Geolocation Data Center
<br> Zone: within the Region for HA.
<br> <b> EBS (Elastic Block Storage):</b>
<br> Partion & create logical volume
<br> EBS is unformated, Throughtput: data transfer per second, IOPS: Input & output per sencod.
<br> Type of EBS: General Purpose (SSD), Porvisioned SSD, Throghput Optimized HDD, SC1: Cold Storage HDD.
<br> It should be in same availability zone.
<br> EBS Snapshots: are used to backup, it will store in amazon S3.
<br> Amazon Data Lifecycle Manager:
<br>EBS Encryption: it is supported to volume.
<br> <b> EFS: Elastic File System</b>
<br> Completely Managed, Lifecyle managment, secure, serverless, EFS shoule not present in same zome.
<br> it can be use as a Content Management System.
<br> <b> Public IP vs Elastic IP</b>:
<br> Public IP : It is not associated with account, No charge, relaunch IP will change.
<br> Elastic IP: it is associated with aws account, charges apply, elatic ip is static.
<br> Elastic Network Interface:
<br><b> Tenancy:</b>
<br> Shared Intance, dedicated instace.
<br> Cross Platform Placement Group: it look underlying hardware, 
<br> Rserved Intance: Prebook instance, much discounted rate.
<br> Spot Instances: Unused EC2 instance on demand price.
<br> <b> FSx: File System</b>
<br> FSx win, FSx Lutster, FSx Netapp
<br> Hight Available, Fully Managed, Fast delivery, Easy intigration.
<br> Features of FSx: DFS (Distributed file system)
Namespace allow you to group.
<br> FSx work with AD, Encryption, KMS, ISO, PCI-DSS, HIPPAA compilate.
<br> VPC: Multiple availability zone, subnet is subset of vpc. 
<br> NACL - Network Access Control List--> 
<br> Security Group: 
<br> Route Table
<br> Private Subnet & Public Subnet: Public could be webserver while private could be database server.
<br> Internet Gateway: 
<br> Nat GateWay: Provide internet to private subnet.
<br> Amazon DynamoDB: is a fast and flexible noSQL DB.
Single Digit Millisecond latency.
<br> Amazon Redshift: Fully Managed Petabytes DB.
<br>Mangament Tools:  Amazon Cloudwatch, AWS Cloud Formation ( Appropirated Order). AWS Cloud Trail: is as web service that records AWS API Callls. IAM, KMS, WAF, API Gateway, Elastic Transcoder.  SNS, SES
<br> Amazon Simple Email Service:
<br> Simple Workflow Service:
<br> Amazon Simple Queue Service:
<br> <b> Amazon  Simple Storage Service</b>
<br>Common use case for Amazon S3 storage:
<br> --> Backup and archive for on-premises or cloud data
<br> --> Content, media and software storage distribution
<br> ---> Big data analysis
<br> --> Cloud Native mobile host 
<br> --> Disaster Recovery
<br>S3 offer configuratble lifecycle polices & using it will be store in most appropriate storage class.
<br> Amazon s3 operataion: create/delete a bucket, Write an object, read an object, delet an object, list keys in bucket.
<br> It is support REST API also.
<br> Storage Classes: Strandard, Standard-IA, RRS, Glacier
<br> Object lifecycle management: Amazon S3 lifecycle management is roughly equivaltent to automated storage tiering.
<br> We can write amazon storeage lifecycle rules.
<br> Encryption: SSE-S3 (AWS Managed Keys), SSE-KMS, SSE-C (customer provided key).
<br> <b>Amazon Machine Image</b>
<br> Four Sources of AMI: Publish by AWS, AWS marketplace,  generate from existing instance, uploaded virtual servers.
<br><b>The lifecycle of Instace:</b> Launching, Bootstrapping, VM Import/Export.
<br> <b> Amazon Elastic Block Store</b>
<br> <b> Amazon Virtual Private Cloud(VPC)</b>: Custom defined virtual private cloud.
<br>An Amazon VPC consists of the fallowing component:
<br> 1. Subnet
<br> 2. Route Table
<br> 3. Dynamic Host Configuration Protocol (DHCP)
<br> 4. Security Group
<br> 5. Network Access Control List(ACLs)






 
