# VoxElecta-Online-Voting-System
Built a secure online voting platform using Java, Hibernate, and MySQL with OTP-based authentication and BCrypt password hashing. Implemented one-vote-per-user logic, real-time results dashboard, and admin panel, following MVC architecture and deployed on Apache Tomcat.
Overview

VoxElecta is a modern, secure, and scalable online voting system built using Java Enterprise technologies. It enables users to register, verify via OTP, and cast votes securely with real-time result visualization.

🎯 Designed for colleges, organizations, and digital elections — eliminating the need for physical booths.

✨ Key Features
🔐 Secure Authentication (BCrypt password hashing)
📱 OTP Verification (Mobile-based)
🗳️ One Person, One Vote
📊 Live Results Dashboard (Auto-refresh + charts)
🧑‍💼 Admin Panel (Candidate management)
🎨 Modern UI (Tailwind CSS)
📷 Candidate Photo Support
⚡ Real-time vote counting
🖼️ Screenshots
🏠 Home Page

🗳️ Voting Page

📊 Results Dashboard

🧑‍💼 Admin Panel

📌 Replace these placeholder images with your actual screenshots (/screenshots folder recommended)

🎥 Demo

🔗 Live Demo:

http://localhost:8085/OnlineVoitingSys/

📺 Video Demo:
👉 https://your-demo-video-link.com

🛠️ Tech Stack
Layer	Technology
Backend	Java, Servlets, Jakarta EE
ORM	Hibernate
Database	MySQL
Frontend	JSP, Tailwind CSS
Charts	Chart.js
Security	BCrypt, OTP (Fast2SMS)
Server	Apache Tomcat
Build Tool	Maven
📂 Project Structure
src/main/java/com/voting/
 ├── model/       # Entities
 ├── dao/         # Database operations
 ├── service/     # Business logic
 ├── servlet/     # Controllers
 ├── util/        # Utilities

webapp/
 ├── jsp/         # UI pages
 ├── images/      # Assets
⚙️ Installation & Setup
🔹 Prerequisites
Java 11+
MySQL 8+
Apache Tomcat 10+
Maven
🔹 Steps
1. Clone Repository
git clone https://github.com/your-username/VoxElecta.git
cd VoxElecta
2. Setup Database
CREATE DATABASE election;
3. Configure Hibernate

Edit:

src/main/resources/hibernate.cfg.xml
<property name="connection.url">jdbc:mysql://localhost:3306/election</property>
<property name="connection.username">root</property>
<property name="connection.password">your_password</property>
4. Build & Run
mvn clean install
Deploy .war file in Tomcat
Start server
5. Open in Browser
http://localhost:8085/OnlineVoitingSys/
🔐 Security Highlights
🔒 BCrypt password hashing
📱 OTP verification (5-minute expiry)
🚫 Double voting prevention
🛡️ SQL Injection protection (Hibernate ORM)
🔑 Session-based authentication
🔄 Application Flow
Register → OTP Verify → Login → Vote → Live Results
🚀 Future Enhancements
📧 Email notifications
📱 Mobile application (Flutter/React Native)
🔗 Blockchain-based voting
📊 Advanced analytics dashboard
🧾 Result export (PDF/Excel)
🤝 Contributing

Contributions are welcome!

Fork the repo
Create your feature branch
Commit changes
Push to branch
Open a Pull Request
👨‍💻 Author

Sumit Kumar Soni
📅 2026
🚀 Version 1.0
