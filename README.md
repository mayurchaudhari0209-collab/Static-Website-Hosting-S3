# 🚀 Static Website Hosting on AWS S3

<p align="center">
  <b>Host a Static Website Using Amazon Web Services (AWS)</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AWS-Amazon%20S3-orange?logo=amazons3&logoColor=white" />
  <img src="https://img.shields.io/badge/Website-Static-blue" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
</p>

## 📌 Project Overview

This project demonstrates how to host a static website using **Amazon Simple Storage Service (Amazon S3)**.

Amazon S3 stores website files such as HTML, CSS, JavaScript, and images. By enabling static website hosting and configuring the required permissions, users can access the website through an S3 website endpoint.

## 🎯 Project Objectives

- Understand Amazon S3 and its features.
- Create and configure an S3 bucket.
- Upload static website files.
- Enable static website hosting.
- Configure bucket permissions for public website access.
- Access the hosted website using its endpoint.

## 🛠️ AWS Services Used

| Service | Purpose |
|---|---|
| Amazon S3 | Stores and hosts website files |
| S3 Bucket Policy | Controls access to website objects |
| S3 Static Website Hosting | Makes the website accessible through a website endpoint |

## 🏗️ Architecture

```text
          👤 User
             |
             v
      🌐 Web Browser
             |
             v
    Amazon S3 Website Endpoint
             |
             v
       🪣 S3 Bucket
             |
             v
    HTML + CSS + Images
```

## ⚙️ Implementation Steps

### 1. Create an S3 Bucket
- Open the AWS Management Console.
- Navigate to Amazon S3.
- Click **Create bucket**.
- Enter a globally unique bucket name.
- Select the required AWS Region.
- Create the bucket.

### 2. Upload Website Files
Upload your website files, for example:

- `index.html`
- `style.css`
- `images/`

### 3. Enable Static Website Hosting
- Open your S3 bucket.
- Go to **Properties**.
- Find **Static website hosting**.
- Click **Edit** and enable it.
- Set the index document to `index.html`.
- Save the changes.

### 4. Configure Permissions
- Open the **Permissions** tab.
- Configure the required public-read access if the project requires a public website.
- Add an appropriate bucket policy for website objects.

**Security note:** Public access should be enabled only when required. For production websites, consider CloudFront with Origin Access Control to keep the S3 bucket private.

### 5. Access the Website
- Open **Properties → Static website hosting**.
- Copy the website endpoint.
- Open the endpoint in a browser to test the website.

## 📚 Key Learnings

- Amazon S3 bucket creation and configuration.
- Static website hosting.
- HTML and CSS file deployment.
- Bucket policies and access permissions.
- AWS website endpoints.
- Basic cloud storage security.

## 💼 Practical Skills Demonstrated

- AWS Management Console
- Amazon S3
- Static Website Deployment
- Cloud Storage
- Access Management
- Basic AWS Security

## 🔮 Future Enhancements

- Configure Amazon CloudFront for HTTPS and content delivery.
- Connect a custom domain using Amazon Route 53.
- Configure AWS Certificate Manager for SSL/TLS.
- Automate website deployment using GitHub Actions.

## 👨‍💻 Author

**Mayur Chaudhari**

B.Sc. Computer Science | Fresher DevOps / AWS Cloud Engineer

🔗 GitHub: [mayurchaudhari0209-collab](https://github.com/mayurchaudhari0209-collab)

---

⭐ If you find this project useful, consider giving the repository a star!

#AWS #AmazonS3 #CloudComputing #StaticWebsiteHosting #DevOps #AWSProjects
