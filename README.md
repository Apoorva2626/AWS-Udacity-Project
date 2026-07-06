# AWS-Udacity-Project
Static website deployed on AWS using Amazon S3 and CloudFront as part of the Udacity Cloud Developer Nanodegree.
# Deploy Static Website on AWS

This project demonstrates how to deploy a static website on Amazon Web Services (AWS) using Amazon S3 and Amazon CloudFront. The website is hosted in an S3 bucket configured for static website hosting and distributed globally through CloudFront for improved performance and low-latency content delivery.

This project was completed as part of the **Udacity Cloud Developer Nanodegree Program**.

---

## Project Overview

The objective of this project is to deploy a static website using AWS cloud services while following best practices for hosting and content distribution.

The deployment includes:

- Hosting website files in Amazon S3
- Enabling Static Website Hosting
- Configuring bucket permissions
- Creating a CloudFront distribution
- Accessing the website through CloudFront

---

## Architecture

```
                User
                  │
                  ▼
         Amazon CloudFront
                  │
                  ▼
     Amazon S3 Static Website
                  │
                  ▼
      HTML • CSS • JavaScript
```

---

## AWS Services Used

### Amazon S3

- Created an S3 bucket
- Uploaded website files
- Enabled Static Website Hosting
- Configured Bucket Policy for public access

### Amazon CloudFront

- Created a CloudFront Distribution
- Configured the S3 website endpoint as the origin
- Delivered website content through the CloudFront URL

---

## Technologies Used

- Amazon S3
- Amazon CloudFront
- AWS IAM
- HTML5
- CSS3
- JavaScript

---

## Project Structure

```
.
├── css/
├── img/
├── vendor/
├── index.html
├── README.md
└── screenshots/
```

---

## Deployment Steps

1. Create an Amazon S3 bucket.
2. Upload the website files.
3. Enable Static Website Hosting.
4. Configure the bucket policy for public access.
5. Create a CloudFront distribution.
6. Set the S3 website endpoint as the origin.
7. Wait for deployment.
8. Open the CloudFront URL to access the website.

---

## Live Demo

**CloudFront URL**


https://d2kbw1rhqp2mjw.cloudfront.net

**Static-website URL**
---

http://my-847479298316-bucket.s3-website-us-east-1.amazonaws.com

---

## Learning Outcomes

Through this project, I gained practical experience with:

- Hosting static websites using Amazon S3
- Configuring Static Website Hosting
- Managing access using Bucket Policies
- Deploying websites with Amazon CloudFront
- Understanding CDN-based content delivery
- Basic AWS infrastructure deployment

---

## Cleanup

After project completion:

- Delete the CloudFront distribution
- Empty and delete the S3 bucket
- Verify no AWS resources remain active

---

## Author

**Apoorva Nimmala**

GitHub: https://github.com/Apoorva2626

LinkedIn: https://www.linkedin.com/in/apoorva-nimmala
