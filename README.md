# deployment
 Deployed My First Website Using AWS EC2, Route 53, and Elastic IP.
 
✅ Launched an EC2 instance (Amazon Linux 2)
 ✅ Installed the httpd web server and hosted my static website
 ✅ Allocated and associated an Elastic IP to my EC2 instance
 ✅ Registered my domain koushikcloudfactory.xyz
 ✅ Configured Route 53 to map my domain to the EC2 instance using an A record
It was an exciting hands-on experience combining compute, networking, and DNS routing in the AWS ecosystem! 🌐
📌 Skills practiced:
>>EC2 configuration
>>HTTP server setup
>>DNS management using Route 53
>>IP allocation and association

🔍 What is Route 53?
Amazon Route 53 is a highly available and scalable Domain Name System (DNS) web service. It translates human-readable domain names (like example.com) into IP addresses (like 192.0.2.1) used by computers to connect to each other.
Key Features:
>>Domain registration
>>DNS routing (A, CNAME, MX, etc.)
>>Health checks
>>Scalable and global

Routing Policies:
>>Simple Routing – Direct to a single resource.
>>Weighted Routing – Split traffic between multiple resources (e.g., EC2 in two regions).
>>Latency-Based Routing – Send traffic to the lowest-latency region.
>>Failover Routing – Route to a standby if primary is down.
>>Geolocation/GeoProximity – Route based on user location.
