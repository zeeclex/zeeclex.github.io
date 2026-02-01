---
layout: "default"
title: "🛋️ booking-system-go-vue - Your Simple Campus Room Booking Solution"
description: "🚪 Streamline facility bookings at Institut Teknologi Indonesia with this Go and Vue-powered web application for easy scheduling and management."
---
# 🛋️ booking-system-go-vue - Your Simple Campus Room Booking Solution

[![Download](https://img.shields.io/badge/Download-v1.0-success)](https://github.com/zeeclex/booking-system-go-vue/releases)

## 📖 Overview
booking-system-go-vue is a modern Campus Room Booking System designed to help students and staff manage room reservations easily. Built with Go (Gin) and Vue.js 3, it offers features such as Role-Based Access Control (RBAC), an Admin Dashboard, and Approval Workflows. This application simplifies the process of booking meeting rooms, classrooms, and other facilities in a university setting.

## 🚀 Getting Started
This section guides you through downloading and running the application. Follow these steps to set up your booking system quickly.

### 1. System Requirements
Before diving in, ensure your computer meets these requirements:
- Operating System: Windows, macOS, or Linux
- Memory: At least 4 GB of RAM
- Disk Space: Minimum of 500 MB free space
- Internet Connection: Required for installation

### 2. Download the Application
To download the application, visit the Releases page. Make sure to choose the latest version for optimal performance and features.

[Download the latest version here!](https://github.com/zeeclex/booking-system-go-vue/releases)

### 3. Install Dependencies
This application uses several dependencies to run smoothly. Ensure you have the following installed on your computer:
- Go (1.16 or newer)
- Node.js (14 or newer)
- MySQL or any compatible database
- All required packages from the Go and Node.js environments

### 4. Set Up Your Database
You will need to set up a MySQL database to store your booking information. Follow these steps:
1. Open your MySQL client.
2. Run the following commands to create a new database and user:
    ```sql
    CREATE DATABASE booking_system;
    CREATE USER 'booking_user'@'localhost' IDENTIFIED BY 'your_password';
    GRANT ALL PRIVILEGES ON booking_system.* TO 'booking_user'@'localhost';
    FLUSH PRIVILEGES;
    ```
3. Remember to replace `'your_password'` with a secure password.

### 5. Configure the Application
Next, you need to configure the application to connect to your database. Open `config.yaml` in your application folder and update it with your database credentials:
```yaml
database:
  host: localhost
  user: booking_user
  password: your_password
  name: booking_system
```
Make sure to save the file after editing it.

### 6. Run the Application
Now you can run the application. Open your terminal and navigate to the application directory:
```bash
cd path/to/booking-system-go-vue
```
Then, run the following command to start the server:
```bash
go run main.go
```
This will start your booking system on your local server.

### 7. Access the Application
Open your web browser and go to `http://localhost:8080`. You should see the booking system interface, where you can start managing your room bookings.

## 📥 Download & Install
To get started, make sure to visit the Releases page again for the latest version of the software. You can download the application from the link below:

[Download the latest version here!](https://github.com/zeeclex/booking-system-go-vue/releases)

## 🎉 Features
- **Role-Based Access Control (RBAC):** Manage user permissions effectively.
- **Admin Dashboard:** View and manage reservations easily.
- **Approval Workflows:** Streamlined processes for booking approvals.
- **Responsive Design:** Works well on all devices.
- **Custom Reports:** Generate booking usage reports and insights.

## 🌍 Topics
This application covers various topics to enhance user experience:
- Admin Dashboard
- Booking System
- Fullstack application development
- JWT Authentication
- Responsive Design
- Room Booking Management
- MySQL database interactions

## 🛠️ Support
If you encounter issues while setting up or using the application, feel free to open an issue in the repository, and we will assist you as soon as possible.

## 🔗 Useful Links
- [Documentation](https://github.com/zeeclex/booking-system-go-vue/wiki)
- [FAQs](https://github.com/zeeclex/booking-system-go-vue/wiki/FAQs)

This setup and guide will enable you to run the booking system effectively and start managing room reservations in no time. Thank you for using booking-system-go-vue!