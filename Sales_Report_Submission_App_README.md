# 📊 Sales Report Submission App  

A mobile application designed for sales staff to upload structured shop visit reports with photos, and for supervisors/admins to view, summarize, and export these reports into Excel with embedded images.  

---

## 🔹 1. Problem Statement  
Sales supervisors and managers need a simple way to collect reports from field staff. Existing tools like Google Forms link uploaded photos to Google Drive, which makes exporting and reviewing cumbersome. The **Sales Report Submission App** provides a mobile-first way for sales staff to upload structured reports (with details + photo evidence) that admins can view, summarize, and export into Excel with embedded photos.  

---

## 🔹 2. Features List  

### For Sales Users (Field Staff)  
- 🔑 User Authentication (Firebase Auth)  
- 📝 Submit Report Form with fields:  
  - Supervisor name (dropdown)  
  - Salesperson name (auto from account or text input)  
  - Location of shop (manual entry or GPS)  
  - Shop name  
  - Material (dropdown or text)  
  - Upload photo (shop/product evidence)  
- 📂 View My Reports (history of submissions)  

### For Admins (Supervisors/Managers)  
- 📊 Admin Dashboard: view all submitted reports  
- 📈 Summary of sales reports (e.g., total visits, total materials distributed)  
- 🔍 Filter by date, salesperson, or region  
- 📤 Export to Excel (with embedded photos, not just Drive links)  
- 📦 Monthly Material Allocation Tracker  

---

## 🔹 3. User Stories  
- As a **salesperson**, I want to upload my shop visit report with photos so my supervisor can verify my work.  
- As a **salesperson**, I want to view my submitted reports so I know they were received.  
- As a **supervisor**, I want to view reports from my assigned region so I can track staff performance.  
- As a **manager/admin**, I want to export reports into Excel with embedded photos so I can archive and share them.  
- As a **manager/admin**, I want to summarize materials given to shops monthly so I can monitor distribution.  

---

## 🔹 4. Technology Stack  

### Mobile App (Android - Kotlin + Jetpack Compose)  
- Language: **Kotlin**  
- UI: **Jetpack Compose**  
- Architecture: **MVVM**  
- Async: **Coroutines + Flow**  
- Dependency Injection: **Hilt**  
- Network: **Retrofit + Moshi (REST API if needed)**  
- Backend: **Firebase Firestore + Firebase Storage**  
- Auth: **Firebase Auth**  

### Admin Tools  
- Option 1: Build a small **web admin panel** (React/Next.js or Flutter Web) connected to Firebase  
- Option 2 (simpler): A **Python/Node.js export script** that fetches Firestore data + Firebase Storage photos and generates an Excel file with embedded images  

  - Python: `openpyxl` for Excel with images  
  - Node.js: `exceljs` for Excel with images  

---

## 🔹 5. Project Timeline  

- **Week 1-2:** Topic selection, problem statement, feature list, Figma mockups  
- **Week 3:** Topic presentation to lecturer  
- **Week 4-6:** Build authentication and basic report submission form  
- **Week 7-8:** Implement photo upload + storage integration  
- **Week 9:** Create "View My Reports" and Admin Dashboard (list view)  
- **Week 10:** Implement summary and filtering for admins  
- **Week 11:** Develop export to Excel with embedded photos  
- **Week 12:** Testing, bug fixing, improve UX  
- **Week 13:** Final presentation and demo  

---

## 🔹 6. Version Control  
- Repository hosted on **GitHub**  
- Branching strategy: `main`, `dev`, `feature/*`  
- Commit history with meaningful messages  

---

✨ This project provides a practical, real-world solution for sales report management, while covering essential Android development and backend integration skills.  
