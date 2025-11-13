 Sales Report Submission App  

A mobile application designed for sales staff to upload structured shop visit reports with photos, and for supervisors/admins to view, summarize, and export these reports into Excel with embedded images.  

1. Project Overview

A mobile application for sales staff to submit daily shop visit reports with photo evidence, and for supervisors to view those reports directly in the same app.
Everything happens inside one Android app using Firebase Authentication, Firestore, and Firebase Storage.

2. Problem Statement

Sales staff often send daily reports through chat or Google Forms.
Photos and report data are scattered and hard to manage.
This app provides a centralized, mobile-first reporting tool — simple enough for small teams, but structured for easy review.

3. Key Features

+ For Salesperson
Login / Register (Firebase Auth)
Submit Report Form
Supervisor name (dropdown or text)
Shop name
Material (dropdown or text)
Notes
Take/Upload Photo
Auto record current date/time
My Reports List
Shows submitted reports (date, shop, material, photo thumbnail)

+ For Supervisor
View All Reports
 Filter by salesperson or date
 Tap to view full report and photo

5. Technology Stack
 Language: Java
 UI: XML + RecyclerView + Glide (for images)
 Architecture: MVP (Model–View–Presenter)
 Backend: Firebase
 Firebase Auth (login/register)
 Firebase Firestore (reports storage)
 Firebase Storage (images)
 Build Tool: Gradle
