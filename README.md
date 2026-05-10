# Event Announcement System

## 📌 Overview
A serverless event announcement and notification system built on **Amazon Web Services (AWS)**.  
This project uses **SNS**, **Lambda**, and **API Gateway** to deliver real-time notifications for upcoming events.  
It enables administrators to announce events and ensures subscribers receive timely updates via email or SMS.

---

## ⚙️ Architecture

- **Amazon S3**: Stores event posters and static assets.
- **AWS Lambda**: Handles backend logic for event creation and notifications.
- **Amazon SNS**: Publishes announcements to subscribers.
- **API Gateway**: Provides REST endpoints for admin interaction.
- **IAM**: Manages secure access and permissions.
- **Frontend**: Simple HTML/CSS/JavaScript interface.

---

## 🚀 Features

- Event creation and management via API Gateway  
- Automated notifications using SNS (email/SMS)  
- Scalable serverless design with Lambda  
- Secure access control with IAM  
- Easy integration with frontend UI  

---

## 🛠️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/username/Event-Announcement-System.git
   cd Event-Announcement-System
   
2.Configure AWS Services

  -Create an SNS topic and add subscriptions.
  -Deploy Lambda functions for event handling.
  -Set up API Gateway endpoints.
  -Assign IAM roles for Lambda and API Gateway.

3.Frontend Setup

  -Place frontend files on a local server or S3 bucket.
  -Update API Gateway endpoint URLs in the frontend code.
  
4.Run the System

  -Admins announce events via the frontend form.
  -Subscribers automatically receive notifications.
  
📊 Future Enhancements

  -Integration with Google Calendar/Outlook
  -Push notifications for mobile apps
  -Analytics dashboard for event engagement
  -Feedback and rating system

📜 License
This project is for academic and learning purposes. You may adapt and extend it for research or organizational use.
