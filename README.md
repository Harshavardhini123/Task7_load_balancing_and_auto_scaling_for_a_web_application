# Task7_load_balancing_and_auto_scaling_for_a_web_application
What I did:

Created an EC2 instance using Amazon Linux 2023 AMI.
Installed Apache Web Server and hosted a simple HTML page.
Configured an Elastic Load Balancer (ELB) and attached backend instance.
Verified target group → Healthy status.
Tested the load balancer URL (connected successfully to instance).
Tried to set up an Auto Scaling Group, but got a VPC/security group linking issue.

What I understood:

Load Balancing helps distribute traffic across multiple servers to keep the app available.
Auto Scaling automatically adds or removes instances based on load, improving cost efficiency.
Learned how health checks work to detect and replace unhealthy instances.
Understood that network and VPC configuration are critical for scalable architecture.
Gained hands-on experience in setting up high-availability architecture on AWS.
