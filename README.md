# Violet Estate - AWS Cloud Deployment Project

## Project Overview

This project documents the design, deployment, and security testing of the Violet Estate real estate website homepage.

The goal of this project was to combine frontend web development with AWS cloud infrastructure by deploying a website on an Ubuntu EC2 server using Nginx and securing it with HTTPS.

This project covers:

- AWS VPC configuration
- EC2 deployment
- Security Group configuration
- S3 bucket setup
- Nginx web server deployment
- Domain configuration
- HTTPS implementation using Let's Encrypt
- Network and service security testing using Nmap


## Website Development

The Violet Estate homepage was designed and developed using:

- HTML
- CSS
- JavaScript
- Visual Studio Code

The homepage design focuses on:

- Modern real estate branding
- Responsive layout
- Property showcase section
- Service sections
- Customer testimonials
- Agent presentation section
- Professional navigation and footer design


## AWS Infrastructure

The cloud environment was deployed using Amazon Web Services (AWS).

Infrastructure components:

### Amazon VPC

Created a custom VPC:

- VPC Name: vio-estate-vpc
- IPv4 CIDR: 192.168.0.0/16


### Subnet

Configured a public subnet:

- Subnet Name: vio-estate-subnet
- CIDR: 192.168.10.0/24


### Route Table

Configured routing for internet communication:

- Custom route table
- Internet Gateway connection


### EC2 Instance

Deployed an Ubuntu EC2 instance:

- Operating System: Ubuntu Linux
- Web Server: Nginx
- Instance Type: t2.medium


## Web Server Configuration

The website was deployed on an Nginx web server.

Deployment process:

1. Installed Nginx on Ubuntu
2. Uploaded website files
3. Configured web root directory
4. Restarted Nginx service
5. Verified public website access


## HTTPS Security

HTTPS was enabled using Let's Encrypt.

Implemented:

- SSL certificate generation
- Nginx HTTPS configuration
- Secure browser communication


## Storage

Amazon S3 was configured as part of the AWS environment for cloud storage management and security planning.


## Security Testing

Security validation was performed using Nmap.

Testing included:

### Port Scanning

Identified exposed services:

- 22/tcp SSH
- 80/tcp HTTP
- 443/tcp HTTPS


### Service Detection

Detected:

- OpenSSH
- Nginx web server
- Ubuntu Linux environment


### SSL Analysis

Reviewed:

- TLS versions
- Supported cipher suites
- HTTPS configuration


## Screenshots

Screenshots documenting the deployment process are included in this repository.


## Learning Outcomes

This project improved my practical understanding of:

- Cloud infrastructure deployment
- Linux server administration
- Web hosting
- Network security
- DNS configuration
- HTTPS implementation
- Security testing methodology


## Author

Vio-07

Cloud Engineering / DevOps Learning Journey
