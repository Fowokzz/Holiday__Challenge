# Holiday__Challenge

# Holiday_Challenge

Using Bastion Host to set up 2 EC2 instances on AWS (use the free tier instances).

Using Ansible to deploy an Nginx web server on these instances.

Set up an ALB(Application Load balancer) to route requests to your EC2 instances.

Using PHP to make sure that each server displays its own Hostname. 


#Important points to note:

Web servers shouldn't be accessible through their respective IP addresses. Access must be only via the load balancer

You should define a logical network on the cloud for your servers.

Your EC2 instances must be launched in a private network.

Your Instances should not be assigned public IP addresses.

You may or may not set up auto scaling(I advice you do for knowledge sake)

You must submit a custom domain name(from a domain provider e.g. Route53) or the ALB’s domain name.
