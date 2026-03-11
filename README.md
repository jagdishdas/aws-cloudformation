# AWS CloudFormation LAMP Stack

This project demonstrates Infrastructure as Code using AWS CloudFormation.

It deploys a complete LAMP stack using a single EC2 instance.

## Architecture

EC2 Instance (t2.micro)
- Apache Web Server
- PHP
- MySQL Database

Security Group
- HTTP (80)
- SSH (22)

## CloudFormation Template

Location:

templates/lamp-stack.json

## Deployment

Deploy using AWS CloudFormation console and provide the required parameters.

## Output

The stack outputs a WebsiteURL which displays a sample PHP page showing:

- Instance hostname
- Instance ID
- Current date and time
- Database connection test
