# Static Portfolio Website using AWS S3 and CloudFront

## Project Description
This project demonstrates hosting a static portfolio website using Amazon S3 and delivering it globally using Amazon CloudFront.

## Website
Personal portfolio website built using HTML, CSS, and JavaScript.

## AWS Services Used
- Amazon S3 – Static website hosting
- Amazon CloudFront – Content Delivery Network (CDN)
- AWS IAM – Access and permissions

## Architecture
User → CloudFront → S3 Bucket

## Live Website
S3 URL: http://ragavi-aws-portfolio.s3-website-us-east-1.amazonaws.com
CloudFront URL: https://de5l4kyxtwo1l.cloudfront.net


## Steps Followed
1. Created a static portfolio website
2. Uploaded website files to an S3 bucket
3. Enabled static website hosting in S3
4. Created a CloudFront distribution
5. Configured S3 as the origin
6. Accessed the website using CloudFront domain

## Outcome
The website is scalable, secure, and loads faster using CloudFront.
