
# 🌐 Cloud Resume Challenge - Sambhu Rajendran

Welcome to my implementation of the [Cloud Resume Challenge](https://cloudresumechallenge.dev/) — a hands-on project that demonstrates my cloud, DevOps, and serverless skills by building and deploying a personal resume website using AWS services.

You can view the site live at 👉 **https://sambhurajendran.com**

---

## 🧱 Overview

This project is built entirely using **AWS** services with **CI/CD automation** via GitHub Actions. It features a responsive static website hosted on S3 and served securely over HTTPS using CloudFront. A serverless backend using AWS Lambda and DynamoDB tracks page views (integration with the frontend coming soon).

---

## 🌍 Architecture

- **Frontend**
  - Static website hosted in an **S3 bucket**
  - Delivered using **CloudFront CDN** for performance and HTTPS support
  - **Namecheap** used to purchase the domain and set up domain forwarding to the CloudFront distribution
  - **AWS Certificate Manager** handles SSL certificates for HTTPS

- **Backend**
  - **AWS Lambda** function tracks the number of site visits (✅ working)
  - **DynamoDB** stores the visit count
  - **API Gateway** and **frontend integration** (coming soon)

- **CI/CD**
  - **GitHub Actions** is configured for deployment
  - A manual "Deploy" button triggers updates to the S3 bucket whenever changes are pushed to the main branch

---

## 🛠️ Technologies Used

| Component         | Service / Tool                         |
|------------------|----------------------------------------|
| Hosting          | AWS S3                                 |
| CDN              | AWS CloudFront                         |
| Domain           | Namecheap (with forwarding)            |
| SSL              | AWS Certificate Manager                |
| Serverless       | AWS Lambda                             |
| Database         | AWS DynamoDB                           |
| Automation       | GitHub Actions                         |
| Languages        | HTML, CSS, Python, YAML                |

---

## 📁 Project Structure



## ✨ Features

- ✅ Fully responsive static resume website
- ✅ Custom domain via Namecheap
- ✅ HTTPS enabled using ACM
- ✅ Hosted on S3 with CloudFront distribution
- ✅ CI/CD using GitHub Actions for deployment
- ✅ Visitor counter using Lambda + DynamoDB (working, frontend integration pending)


---

## 👨‍💻 About Me

I'm **Sambhu Rajendran**, a CISSP, Security+, AWS Solutions Architect – Associate certified professional with a background in networking, cloud, and cybersecurity. This project represents my journey into **DevSecOps** and my passion for hands-on learning.

🔗 [LinkedIn](https://www.linkedin.com/in/sambhurajendran)  
📧 sambhurajendran10@gmail.com

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
