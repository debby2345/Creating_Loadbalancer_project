# Creating_Loadbalancer_project
This project document the process of Creating an Target group and load balancer.
### Target Group Creation
Choose "Instance" as the target type.
![targetgroup](/targetgroup_configuration.PNG)

Named the target group,
Selected HTTP as the protocol and port 80,
Choose "IPv4" as the IP address type,
Selected the default VPC.
![targetgroup name](/targetgroup_nmae_vpc.PNG)

Configured HTTP health checks.
![health check](/healthcheck.PNG)

### Targets Registered 
Successfully registered the target group with an instance ID.
![target Successfully](/targetgroup_successful.PNG)

### Application Load Balancer Creation
Named the load balancer,
Choose "Internet-facing" as the scheme,
Selected "IPv4" as the IP address type.
![load balancer](/load_balancer_name.PNG)

### Availability Zones and Subnets
Choose the default VPC for network mapping,
Selected three availability zones and subnets.
![load balancer](/network_mapping.PNG)

### Security Groups
Choose the default security group,
Selected HTTP as the protocol and port 80
![load balancer](/security_group.PNG)

### Load Balancer Creation Successful
Successfully created the load balancer
![load balancer](/loadbalancer_successful.PNG)