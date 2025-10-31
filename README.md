# My AWS EC2 Website Hosted Using Apache

This is a small project where I hosted a simple static website on an AWS EC2 instance using Apache.  

## Project Overview
- Platform: **AWS EC2**
- OS: **Amazon Linux**
- Web Server: **Apache**
- Repository: **GitHub**
- Website Type: **Static HTML**

### 1. Launch an EC2 Instance
- Selected **Amazon Linux 2023**
- Instance type: `t3.micro`
- Allowed ports:
  - SSH (22) – My IP
  - HTTP (80) – Anywhere (0.0.0.0/0)
- Connected to the instance using SSH from my terminal

### 2. Install Apache

sudo dnf update -y
sudo dnf install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd

#### Then I checked if Apache was running by visiting my EC2’s public IP in the browser.

I created an index.html file inside /var/www/html:
cd /var/www/html
sudo nano index.html

##### Then opened it in my browser using:
http://44.201.140.239/

###### YT link
https://youtu.be/gDq7VwFIK6Y



