# 🌘 Eclipse Attendance App

A web-based QR code attendance management system designed for classrooms and labs.  
The application provides **Teacher and Student dashboards**, QR-based attendance marking, and a clean, interactive UI.

This project is a **frontend-only prototype** built using HTML, CSS, and JavaScript to demonstrate session handling, UI logic, and data export.

---

## 🚀 Features

### 👩‍🏫 Teacher Dashboard
- Create or change attendance sessions (subject & date)
- Generate QR code for the active session
- View live attendance table
- Search students by name
- Filter by present / absent status
- Manually mark attendance
- Download attendance data as CSV

### 👨‍🎓 Student Dashboard
- Select student name
- Scan QR (simulated) using modal
- Mark attendance for active session
- View personal attendance history

### ⚙️ Additional UI Features
- Dark mode toggle
- Profile page (role-based view)
- Settings page
- Responsive card-based layout
- Sticky navigation bar

---

## 🧠 How It Works

1. Teacher starts an attendance session  
2. System generates a QR code for the session  
3. Student selects their name and scans the QR  
4. Attendance is marked as **Present**  
5. Teacher can review and export records  

> Note: QR scanning is simulated for academic demonstration purposes.

---

## 🛠️ Tech Stack

- HTML5 – Structure  
- CSS3 – Styling & Dark mode  
- JavaScript (Vanilla) – Application logic  
- QRCode.js (CDN) – QR generation  
- Blob API – CSV export  

No backend or database is used.

---

## 📁 Project Structure

```
eclipse-attendance-app/
├── index.html
├── README.md
└── LICENSE
```

---

## 📊 Data Handling

- Student list is preloaded
- Attendance stored in JavaScript objects
- Session-wise attendance history
- Data resets on page refresh
- CSV export supported

---

## ⚠️ Limitations

- No real QR scanning (camera not used)
- No authentication system
- No backend or database
- Data is not persistent

These are intentional for a frontend-only prototype.

---

## 🔮 Future Enhancements

- Real QR scanning via device camera
- Backend integration (Node.js / Firebase)
- User authentication (Teacher / Student)
- Persistent cloud storage
- Mobile PWA support

---

## 👤 Author

**PADAKANTI HARSHITH**  
Computer Science & Engineering Student  

---

## 📄 License

This project is licensed under the **MIT License**.
