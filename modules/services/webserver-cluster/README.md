# Terraform Web Server Cluster Module

This respository contains a Web Server Cluster module of a [Terraform](https://www.terraform.io/) config.

It define a cluster of web servers module on AWS (Amazon Web Services) using EC2 and Auto Scaling, and a load balancer using ELB.

The cluster of web servers returns "Hello, World" for the URL `/`. The load balancer listens on port 80.

Feel free to update the script for the ASG Launch Config based on your use cases.

## Prerequisites

- You must have [Terraform](https://www.terraform.io/) installed on your computer.
- AWS CLI v2
- [AWS (Amazon Web Services)](http://aws.amazon.com/) account and its credentials set up for your AWS CLI.
