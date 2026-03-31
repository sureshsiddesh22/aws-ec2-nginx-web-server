# AWS EC2 Nginx Web Server Project

## Project Overview
This project demonstrates how to launch an EC2 instance and deploy a custom website using Nginx on AWS.

The goal of this project was to understand how cloud servers work and how applications are deployed in the cloud.

---

## AWS Services Used
- Amazon EC2
- AWS IAM
- Security Groups
- Amazon Linux

---

## Architecture
User → Internet → Security Group → EC2 Instance → Nginx → Website

---

## Steps I Performed

Step 1
Created AWS Free Tier Account

Step 2
Created IAM User for secure login

Step 3
Launched EC2 Instance (Amazon Linux)

Step 4
Connected to EC2 using EC2 Instance Connect

Step 5
Installed Nginx Web Server

Step 6
Created custom website (index.html)

Step 7
Deployed website to Nginx server

Step 8
Configured Security Groups to allow HTTP traffic

---

## Commands Used

Update Server
sudo dnf update -y

Install Nginx
sudo dnf install nginx -y

Start Nginx
sudo systemctl start nginx

Enable Nginx
sudo systemctl enable nginx

Deploy Website
sudo cp index.html /usr/share/nginx/html/index.html

---

## What I Learned
- How EC2 instances work
- Basic Linux commands
- How to install software on a cloud server
- How websites are deployed on servers
- Security group configuration
- Cloud architecture basics

---

## My AWS Learning Journey

Project 1
EC2 Web Server Deployment ✅

Project 2
Static Website Hosting using S3 (Coming Next)

Project 3
Load Balancer + Multiple EC2 Instances

Project 4
CI/CD Pipeline Deployment

## Project Screenshots
