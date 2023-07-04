**AWS Multi-Region Disaster Recovery: Active Standby**


This project aims to deploy a scalable, highly available, and secure web application on AWS using an active standby approach for disaster recovery. The solution leverages multiple AWS regions to ensure resilience and continuity of critical workloads in the event of failures or disasters.

Features:
Automated provisioning of web servers using Auto Scaling Groups (ASG) and Launch Configurations (LC).
Integration with AWS Application Load Balancer (ALB) for load distribution and high availability.
VPC peering between regions for private communication and seamless failover.
Monitoring and scaling policies based on CPU utilization thresholds.
S3 bucket for artifact storage and retrieval.
Route 53 with failover routing policy for global traffic management.
Verification tests for various failure scenarios, including AZ, instance, region, and service failures.
