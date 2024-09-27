# Route_53_Hosted_Zones_VPN_Access

Build a private, internal DNS system using AWS Route 53 Private Hosted Zone, that will allow internal AWS resources (e.g., EC2 instances, databases) to communicate using custom domain names that are only accessible via private network (such as through a VPN).

The goal is to create a secure, isolated network where users or services in local office can access AWS-hosted resources without exposing them to the public internet.

# Steps:

Step 1: Create a VPC
Step 2: Set Up Route 53 Private Hosted Zone
Step 3: Launch EC2 Instances
Step 4: Configure VPN Gateway
