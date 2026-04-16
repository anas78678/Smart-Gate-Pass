🚀 SmartGatePass

 A smart Android-based Gate Pass Management System designed to automate and secure the exit process in colleges and universities using QR Code and Firebase.

📌 Overview

SmartGatePass is a digital solution that replaces traditional manual gate pass systems. <br> It enables students to request gate passes online, allows HODs to approve/reject requests, and ensures secure verification at the gate using QR code scanning.

🎯 Objective

- Automate the college exit process  
- Improve security and transparency  
- Enable real-time tracking of student movement  
- Reduce manual paperwork  

👥 User Roles

The system consists of "4 types of users"

👨‍🎓 Student

- Create account (stored in Firebase RTDB)
- Login to dashboard
- Create new gate pass request
- View all requests (My Requests)

👨‍🏫 HOD (Head of Department)

- View gate pass requests (filtered by department)
- Approve or Reject requests
- Only sees requests of their own department (e.g., BCA HOD sees only BCA students)

🛡️ Guard
- Scan QR code at the gate
- Verify pass validity (Valid / Expired)
- Allow or deny exit

👨‍💼 Admin
- Login using Firebase Authentication
- Manage HODs (Add/Delete)
- Manage Guards (Add/Delete)

---

✨ Key Features

- 🔐 Secure Authentication System  
- 📄 Digital Gate Pass Request System  
- 🧾 Department-wise Request Filtering  
- 📷 QR Code Generation on Approval  
- ⏳ Time-based Pass Expiry (6 Hours Validity)  
- 🔍 Real-time QR Verification at Gate  
- ☁️ Firebase Realtime Database Integration  
- 👥 Multi-role Access System  

🔄 System Workflow

1. Student registers and logs into the app  
2. Student creates a new gate pass request  
3. Request is stored in Firebase RTDB  
4. HOD views requests (filtered by department)  
5. HOD approves or rejects the request  
6. If approved → QR Code is generated  
7. Pass remains valid for **6 hours only**  
8. Guard scans QR code at the gate  
9. System checks validity (Valid / Expired)  
10. Entry/Exit is recorded  

---

## 🛠️ Tech Stack

| Layer        | Technology |
|-------------|-----------|
| Frontend     | Android (Java, XML) |
| Backend      | Firebase Realtime Database |
| Authentication | Firebase Authentication |
| QR Scanner   | ZXing Library |
| IDE          | Android Studio |

---

## 🗂️ Project Structure


SmartGatePass<br>
│<br>
├── activities      
├── adapters          
├── models            
├── firebase        
├── utils          
└── res             


🔥 Firebase (Spark Plan)

- Free tier (Spark Plan)
- Realtime Database support
- Authentication support
- Suitable for small to medium scale apps


 🚀 Future Enhancements

- Face Recognition-based Entry System  
- Push Notifications for approvals  
- Advanced Admin Dashboard  
- Cloud Firestore Migration  
- Role-based Access Control Improvements  
 📥 Download

👉 Download latest APK from Releases:  
https://github.com/anas78678/Smart-Gate-Pass/releases

👨‍💻 Developer
*Mohd Anas*

📜 License

This project is developed for educational purposes.

⭐ Support

If you like this project, give it a ⭐ on GitHub!
