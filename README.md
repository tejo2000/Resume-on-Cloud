# Resume-on-Cloud

This repository contains the code and infrastructure as code (IaC) setup for a dynamic resume website, which displays real-time visitor counts and is deployed using AWS services.

## Technologies Used

- **AWS S3**: Hosts static website content.
- **AWS CloudFront**: Serves content from AWS S3 across the globe.
- **AWS Lambda**: Handles backend logic for visitor counting.
- **AWS API Gateway**: Provides an HTTP endpoint for the Lambda function.
- **AWS DynamoDB**: Stores and retrieves visitor count data.
- **AWS Route 53**: Manages custom domain.
- **AWS SAM**: Deploys and manages infrastructure as code.

## Features

- Real-time visitor counting on the website.
- Fully serverless backend architecture.
- Custom domain management through AWS Route 53.
- Secure HTTPS traffic using AWS Certificate Manager.

## Infrastructure as Code

The `template.yaml` file in this repository defines all required AWS resources using AWS SAM (Serverless Application Model), which simplifies the management and deployment of AWS resources.

## Setup Instructions

### Prerequisites

- AWS CLI installed and configured.
- SAM CLI installed.
- Node.js and npm installed (if running scripts or local development).
