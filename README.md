# 🚀 AWS S3 to Lambda Automation Project

This project demonstrates how to automate CSV file processing using **AWS S3** and **AWS Lambda**.

## 🔧 Features
- Upload CSV files to S3 input bucket
- Trigger Lambda automatically
- Transform data (date, volume, % change)
- Output processed files to S3 output bucket

## 🧠 Technologies Used
- AWS Lambda (Python 3.9)
- AWS S3 (Input/Output)
- CloudWatch for logging
- Boto3 (AWS SDK for Python)

## 📂 Folder Structure
├── Input-data/
├── Output-data/
└── lambda_function.py


## 📺 YouTube Tutorial
[[Watch Full Video](https://www.youtube.com/watch?v=bHzDbgy_OaI)](#)

## 🤝 Let's Connect
- [[LinkedIn](https://www.linkedin.com/in/saad-shaikh-05244726b/)](#)
- [[GitHub](https://github.com/Muhammad-Saad12345)](#)

---

### 📌 How to Run
1. Clone this repo
2. Create S3 bucket with folders `Input-data` and `Output-data`
3. Create Lambda function and deploy the code
4. Set trigger with S3 event on `Input-data/*.csv`
5. Upload a CSV file and check `Output-data/`

---

### 🏷️ Tags
`AWS`, `Lambda`, `S3`, `Automation`, `Serverless`, `Python`, `Data Engineering`, `Cloud Projects`

