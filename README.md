# ECS-Service-with-Load-Balancers



Application Load Balancers offer several features that make them attractive for use with Amazon ECS services. Each service can serve traffic from multiple load balancers and expose multiple load balanced ports by specifying multiple target groups. They are supported by tasks hosted on both Fargate and EC2 instances. Application Load Balancers allow containers to use dynamic host port mapping (so that multiple tasks from the same service are allowed per container instance). Application Load Balancers support path-based routing and priority rules (so that multiple services can use the same listener port on a single Application Load Balancer).

