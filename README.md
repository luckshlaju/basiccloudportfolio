# Professional Portfolio on AWS

## Project Objective
To design and deploy a professional portfolio website that showcases my skills, projects, and educational background, using AWS services for scalable and global delivery.

## Technologies Used
- HTML, CSS, JavaScript
- Amazon S3 – Static Website Hosting
- Amazon CloudFront – Global Content Delivery Network (CDN)
- Git & GitHub – Version Control and Documentation

## Architecture Overview
This project follows a static website architecture.  
All frontend files are stored in an Amazon S3 bucket, while Amazon CloudFront is used as a CDN to deliver the website globally with HTTPS, caching, and low latency.

## Deployment Process
1. Designed a responsive portfolio using HTML, CSS, and JavaScript.
2. Created an Amazon S3 bucket and enabled static website hosting.
3. Uploaded all website files to the S3 bucket.
4. Configured bucket permissions to allow access only through CloudFront.
5. Created a CloudFront distribution with the S3 bucket as the origin.
6. Set `index.html` as the default root object in CloudFront.
7. Verified the deployment using the CloudFront distribution URL.

## Live Website
👉 https://d3nx8ri497llyq.cloudfront.net

## Author
**Luckshvadhan B**  
Information Technology Student
