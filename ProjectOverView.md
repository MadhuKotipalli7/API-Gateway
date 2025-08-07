
# 🚀 Serverless AWS Project: API Gateway + Lambda + S3 Static Website Integration

This project demonstrates a real-world **serverless architecture** using AWS Lambda, Amazon API Gateway, and Amazon S3. The goal was to integrate a backend Lambda function with a static frontend hosted on S3 via API Gateway.

---

## 🔧 1. Lambda Function Setup

- ✅ Developed a Python-based AWS Lambda function to handle dynamic inputs and return responses.
- ✅ Deployed the function using AWS Lambda Console and integrated it with API Gateway.
- ✅ Tested the function independently and via API calls.

---

## 🌐 2. API Gateway Configuration

- ✅ Created a REST API in Amazon API Gateway.
- ✅ Defined resources and HTTP methods (`GET`, `POST`) as required.
- ✅ Integrated the API Gateway with Lambda using its ARN.
- ✅ Deployed the API under a production stage to generate a live endpoint.

---

## 🖼️ 3. Static Website Hosting (S3)

- ✅ Created a clean `index.html` page with JavaScript to call the API Gateway endpoint.
- ✅ Created an S3 bucket and enabled **Static Website Hosting**.
- ✅ Uploaded frontend files and updated bucket policy for public access.

Example Bucket Policy:
```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Sid": "PublicReadGetObject",
      "Effect": "Allow",
      "Principal": "*",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::your-bucket-name/*"
    }
  ]
}
```

---

## 🔁 4. Complete Integration and Testing

- ✅ Accessed the static site using the S3 Website URL.
- ✅ Triggered the Lambda function through API Gateway via JavaScript on the frontend.
- ✅ Validated end-to-end flow and tested with different input scenarios.

---

## ✅ Key Learnings

- Deepened understanding of **Serverless Architecture** using AWS services.
- Hands-on experience with **API Gateway**, **Lambda triggers**, and **S3 hosting**.
- Gained skills in **frontend-backend integration** using cloud-native services.

---

## 📌 Tech Stack

- **AWS Lambda**
- **Amazon API Gateway**
- **Amazon S3**
- **Python (for Lambda)**
- **HTML/CSS/JavaScript** (for frontend)

---

## 🎯 Future Improvements

- Add CI/CD pipeline using GitHub Actions + AWS CLI.
- Enable logging and monitoring with CloudWatch.
- Parameterize API endpoint using environment configs.

---

## 🤝 Let’s Connect

If you're working on similar serverless or cloud-native architectures, feel free to connect and collaborate!

---

## 📢 Tags

`#AWS` `#Lambda` `#API Gateway` `#S3` `#Serverless` `#CloudComputing` `#DevOps` `#Python` `#CloudEngineer` `#InfrastructureAsCode`
