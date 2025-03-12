# Serverless Web Application Deployment on AWS

## 🚀 Project Overview
This project demonstrates a fully serverless web application deployed on AWS, leveraging services such as AWS Lambda, API Gateway, Amazon S3, and DynamoDB to deliver a scalable and cost-effective solution.

### 🔗 Useful Links
- [GitHub Repository](<[INSERT_GITHUB_LINK_HERE](https://github.com/Pratik-Khose/Serverless-Web-App-Over-AWS)>)
- [Project Documentation](<https://pratikkhose.medium.com/building-deploying-serverless-web-application-over-aws-cloud-part-01-2c5944a4f722>)
- [YouTube Demo](<https://www.youtube.com/watch?v=caG6TiKph3M&t=291s>)

---

## 📋 Features
- ✅ Fully serverless architecture using AWS Lambda and API Gateway  
- ✅ Static website hosting via Amazon S3  
- ✅ Data storage with Amazon DynamoDB  
- ✅ Automated deployment using AWS SAM/CloudFormation  
- ✅ CI/CD pipeline with AWS CodePipeline  
- ✅ Secure authentication and authorization with AWS Cognito  

---

## 🛠️ Architecture Diagram
![Architecture Diagram](<INSERT_ARCHITECTURE_IMAGE_LINK_HERE>)

---

## ⚙️ Prerequisites
- AWS Account with necessary permissions
- Node.js and npm/yarn installed
- AWS CLI configured with your credentials
- AWS SAM CLI for deployment

---

## 📦 Installation and Setup
1. **Clone the repository**
```bash
git clone <INSERT_GITHUB_LINK_HERE>
cd <PROJECT_FOLDER>
```

2. **Install dependencies**
```bash
npm install
```

3. **Configure AWS resources**
- Create an S3 bucket for static website hosting
- Set up Lambda functions, API Gateway, and DynamoDB using AWS SAM/CloudFormation

4. **Deploy the application**
```bash
sam build
sam deploy --guided
```

5. **Access the application**
- Visit the API Gateway endpoint for the backend
- Access the static website hosted on S3

---

## 🧪 Testing
- Use **Postman** or **curl** to test API endpoints.
- For front-end testing, ensure S3 bucket permissions allow public read access.

---

## 📈 Monitoring and Logging
- AWS CloudWatch is configured for detailed logs and metrics.
- Use CloudWatch dashboards for performance insights.

---

## 🛡️ Security Best Practices
- Use IAM roles with minimal permissions.
- Enable encryption for data in transit and at rest.
- Set up AWS WAF for added protection.

---

## 🚨 Troubleshooting
- **S3 Access Denied?** Ensure bucket policies allow public read access.  
- **Lambda Timeout?** Increase the function timeout in AWS Console.  
- **API Gateway Errors?** Verify endpoint routes and permissions.

---

## 🙌 Contributing
Contributions are welcome! Feel free to submit pull requests or open issues for improvements.

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).
