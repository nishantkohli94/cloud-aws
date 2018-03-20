# AWS Assignemt Day-2

[![N|Solid](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5c/AWS_Simple_Icons_AWS_Cloud.svg/100px-AWS_Simple_Icons_AWS_Cloud.svg.png)](https://nodesource.com/products/nsolid)


### Task 1
> Create a vpc not by wizard this time but manually, having 2 public subnets and 2 private subnets and 2 protected subnets.
### Task 2
> Make LAMP setup with 2 instances in each private subnets. 
> Server-1 should serve a webpage that would say "Hi! i am server 1"
> Server-2 should serve a webpage that would say "Hi! i am server 2"

### Task 3
> Launch a public load balancer that would forward the requests to these 2 LAMP instances
> create the same setup using aws-cli except vpc

#  NOTE!
  - Machines in the protected subnets won't be able to go to internet and vice versa (verify this by launching an instance in this subnet)
  - Make Documentation and push to the repo

