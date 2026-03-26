# aws-ec2-s3-website-hosting
AWS cloud project demonstrating website hosting on EC2 with image storage in Amazon S3.
# AWS EC2 Website Hosting with Image Storage in S3

## Project Overview

This project demonstrates hosting a simple website on an AWS EC2 instance and storing images in Amazon S3. The objective of this project is to gain hands-on experience with AWS cloud services, Linux server setup, and cloud storage integration.

## AWS Services Used

* Amazon EC2
* Amazon S3
* AWS IAM
* Security Groups

## Technologies Used

* Linux (Ubuntu)
* Apache Web Server
* HTML
* SSH

## Architecture

In this project:

* A website is hosted on an Ubuntu EC2 instance.
* Apache Web Server serves the website.
* Website images are stored in an Amazon S3 bucket.
* The HTML page loads images using the S3 object URL.

## Implementation Steps

### 1 Launch EC2 Instance

* Created an Ubuntu EC2 instance
* Allowed SSH (22) and HTTP (80) in Security Group

### 2 Connect to EC2

Connected using SSH.

### 3 Install Apache Web Server

Commands used:

sudo apt update
sudo apt install apache2

### 4 Deploy Website

Uploaded the HTML website file to:

/var/www/html/

### 5 Create S3 Bucket

* Created an S3 bucket
* Uploaded website images

### 6 Integrate S3 Image with Website

Used the S3 object URL in the HTML file to display images on the EC2 hosted website.

## Project Screenshots

Screenshots will be added in the **screenshots** folder showing:

* EC2 instance running
* Apache installation
* Website output
* S3 bucket configuration

## Learning Outcomes

* Launching and managing AWS EC2 instances
* Installing Apache on Linux server
* Using Amazon S3 for object storage
* Integrating EC2 with S3
* Understanding basic cloud architecture

## Author

Mohammad Rahil
## Project Screenshots

### AWS EC2 Ubuntu Instance
screenshots/AWS EC2 Ubuntu Instance.png

### Apache Web Server Installation
screenshots/Apache Web Server Installation on EC2.png
### Website Hosted on EC2 with Image from S3
screenshots/Website Hosted on EC2 with Image from S3.png

### Amazon S3 Storage Bucket
screenshots/Amazon S3 Storage Bucket.png

### Image Stored in Amazon S3
screenshots/Screenshot Image Stored in Amazon S3.png
