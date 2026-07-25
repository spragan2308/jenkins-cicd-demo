# CI/CD Pipeline using Jenkins, GitHub and AWS EC2

## Project Overview
This project demonstrates a complete CI/CD pipeline where application code is managed using GitHub, automatically built using Jenkins, and deployed on an AWS EC2 server.

## Tools & Technologies Used

- AWS EC2
- Linux (Ubuntu)
- Jenkins
- Git & GitHub
- GitHub Webhooks
- Apache Web Server
- HTML

## CI/CD Workflow

Developer
   ↓
GitHub Repository
   ↓
GitHub Webhook
   ↓
Jenkins Build Automation
   ↓
Deployment to AWS EC2
   ↓
Live Website

## Project Implementation

### 1. AWS EC2 Setup
- Created an Ubuntu EC2 instance.
- Installed and configured Jenkins.
- Installed Apache Web Server for hosting.

### 2. Jenkins Configuration
- Created Jenkins job.
- Added Execute Shell build steps.
- Verified successful Jenkins builds.

### 3. GitHub Integration
- Connected GitHub repository with Jenkins.
- Configured GitHub Webhook for automatic triggering.

### 4. Deployment
- Automated deployment of website files.
- Deployed index.html to Apache web server.

## Screenshots

### Jenkins Successful Build
(Add Jenkins screenshot here)

### GitHub Webhook Success
(Add Webhook screenshot here)

### AWS EC2 Instance
(Add EC2 screenshot here)

### Live Website Output
(Add website screenshot here)

## Result

Successfully implemented an automated CI/CD pipeline using Jenkins, GitHub, and AWS EC2.
