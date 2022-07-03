# Auto Scaling Groups (ASG)

_“An Amazon EC2 Auto Scaling Group (ASG) contains a set of EC2 instances that share similar characteristics and are treated as a logical grouping for fleet management and dynamic scaling purposes.”._

- In real-life, the load on your websites and application can change
- In the cloud, you can create and get rid of servers very quickly

The main goals of an Auto Scaling Group is to:

- **Scale out** (add EC2 instances) to match an increased load
- **Scale in** (remove EC2 instances) to match a decreased load
- Ensure we have a minimum and a maximum number of machines running
- Automatically Register new instances to load balancer
