# Automating Cloud Provisioning Using AWS CloudFormation

This project demonstrates how to automate the provisioning of cloud infrastructure using AWS CloudFormation with JSON templates. Instead of manually configuring each cloud service, this approach uses Infrastructure as Code (IaC) to launch a full WordPress environment on AWS within minutes.

## 📌 Project Overview

Traditional cloud setup requires manually provisioning servers, databases, and configurations. This process is time-consuming and error-prone. This project uses AWS CloudFormation to automate the deployment of infrastructure using a simple JSON-formatted template, making the process efficient, repeatable, and secure.

## 🚀 Features

- Fully automated WordPress setup on an EC2 instance
- MySQL database configuration with secure credentials
- JSON-based AWS CloudFormation template
- Auto rollback on failure for reliable provisioning
- Infrastructure as Code approach for reusability and compliance

## 🧰 Technologies Used

- AWS CloudFormation
- Amazon EC2
- Amazon RDS (MySQL)
- JSON
- Linux (Ubuntu)
- Apache & PHP

## 🛠️ How It Works

1. Upload the CloudFormation JSON template to AWS Console
2. Provide parameters like DB name, user, passwords, etc.
3. AWS provisions all necessary resources
4. Access your WordPress setup at `http://<EC2-IP>/wordpress`

## 📁 Project Structure

- `template.json`: The CloudFormation template file
- `README.md`: Project documentation
- `/screenshots`: Output images (optional)

## 📝 How to Run

1. Log into the [AWS CloudFormation Console](https://console.aws.amazon.com/cloudformation)
2. Upload the `template.json` file
3. Fill in required stack parameters
4. Launch the stack
5. After deployment, access the WordPress site using the EC2 Public IP

## 📌 Benefits

- Saves time by automating infrastructure provisioning
- Ensures repeatability and consistency across environments
- Reduces human error with predefined templates
- Supports multi-region deployment and automatic rollback

## Documentation
https://drive.google.com/drive/u/0/folders/1BNKYBuHZorpS3Vn_Ipwt9CF7K2zvUWgV


