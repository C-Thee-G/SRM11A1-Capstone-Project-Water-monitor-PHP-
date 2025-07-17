# Water Monitoring System 🚰💧

![PHP](https://img.shields.io/badge/PHP-8.0+-777BB4?logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-8.0+-4479A1?logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.2+-7952B3?logo=bootstrap&logoColor=white)

A comprehensive water consumption tracking system with leak detection, conservation tips, and reward incentives.

## Screenshots
<img width="1366" height="768" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/1407d9a9-7bbc-46d8-a5b1-fa0c42ab0a7f" />
<img width="1366" height="768" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/94442943-a93b-4bb6-8243-7e157ed64dfa" />
<img width="1366" height="768" alt="Screenshot (3)" src="https://github.com/user-attachments/assets/b5a4f51e-6f8b-461c-b734-d3cb284c5800" />
<img width="1366" height="768" alt="Screenshot (4)" src="https://github.com/user-attachments/assets/f40d79f1-1697-4425-bed8-1b8d94c95a4a" />
<img width="1366" height="768" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/823b0ebc-545c-454a-a935-8bfb5657ebe0" />
<img width="1366" height="768" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/eea7f243-b66a-45ed-9b41-73f5201a00ff" />
<img width="1366" height="768" alt="Screenshot (7)" src="https://github.com/user-attachments/assets/7a31cf8f-9ddb-488d-a4ff-382865897270" />
<img width="1366" height="768" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/c62dbf56-e3a7-4d25-b246-c25eb8c8389d" />
<img width="1366" height="768" alt="Screenshot (9)" src="https://github.com/user-attachments/assets/a46a7232-4c2b-499a-97ad-9f5801645b6c" />
<img width="1366" height="768" alt="Screenshot (10)" src="https://github.com/user-attachments/assets/beab6699-d9cc-4073-9b80-d54b5d5ef6ad" />
<img width="1366" height="768" alt="Screenshot (11)" src="https://github.com/user-attachments/assets/a35cc812-7804-47eb-a93b-20ef79962857" />
<img width="1366" height="768" alt="Screenshot (12)" src="https://github.com/user-attachments/assets/bd413c9f-000a-4bd3-b672-969bbd65f745" />




## 📋 Database Schema Overview

### Key Tables
- **users** - Customer and admin accounts
- **water_usage** - Daily water consumption records
- **water_leaks** - Reported/maintained leak incidents
- **conservation_tips** - Water-saving recommendations
- **user_rewards** - Incentive tracking system
- **penalties** - Excessive usage penalties

## 🛠️ Installation

### Prerequisites
- PHP 8.0+
- MySQL 8.0+
- Web server (Apache/Nginx)

### Setup Steps
1. Clone repository:
   ```bash
   git clone https://github.com/yourusername/SRM11A1-Capstone-Project-Water-monitor-PHP.git
Import database:

bash
mysql -u username -p water_monitor < database/schema.sql
Configure .env file:

ini
DB_HOST=localhost
DB_NAME=water_monitor
DB_USER=root
DB_PASS=

### 🌟 Key Features
Real-time water usage tracking

AI-powered leak detection alerts

Personalized conservation tips

Reward point incentive system

Neighborhood consumption benchmarking

Admin dashboard for municipality staff

### 🧑‍💻 Admin Access
Default admin credentials:

Username: admin

Password: Admin@123

### 📊 Sample Data
The database comes pre-loaded with:

10 water conservation tips

System configuration settings

Sample admin user

### 📜 License
This project is licensed under the MIT License.

### 📧 Contact
For implementation inquiries or customization requests:
📩 ncubemcliff@gmail.com

