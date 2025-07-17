# Water Monitoring System 🚰💧

![PHP](https://img.shields.io/badge/PHP-8.0+-777BB4?logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-8.0+-4479A1?logo=mysql&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.2+-7952B3?logo=bootstrap&logoColor=white)

A comprehensive water consumption tracking system with leak detection, conservation tips, and reward incentives.

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
🌟 Key Features
Real-time water usage tracking

AI-powered leak detection alerts

Personalized conservation tips

Reward point incentive system

Neighborhood consumption benchmarking

Admin dashboard for municipality staff

🧑‍💻 Admin Access
Default admin credentials:

Username: admin

Password: Admin@123

📊 Sample Data
The database comes pre-loaded with:

10 water conservation tips

System configuration settings

Sample admin user

📜 License
This project is licensed under the MIT License.

📧 Contact
For implementation inquiries or customization requests:
📩 ncubemcliff@gmail.com

