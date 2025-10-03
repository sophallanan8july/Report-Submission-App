# 📱 Community Fan App  

A mobile application designed for fans of games, music, sports, or movies to connect, share posts, and interact in a focused community space.  

---

## 🔹 1. Problem Statement  
Fans often gather across noisy platforms like Facebook, Reddit, or Discord. There is no lightweight, dedicated space where they can connect around a specific interest. The **Community Fan App** solves this by providing a simple and clean app experience with posts, groups, and interaction features tailored for fan communities.  

---

## 🔹 2. Features List  
- 🔑 User Authentication (Firebase Auth: register/login)  
- 📝 Posts Feed (text, images, links)  
- ❤️ Likes & 💬 Comments system  
- 📂 Fan Groups/Categories (e.g., News, Fan Art, Discussion)  
- 👤 Profile Page (user info and posts)  
- 🔔 Notifications for new posts in subscribed categories  
- 🌐 App Resources: Multi-language support (English + Khmer), Dark/Light theme  

---

## 🔹 3. User Stories  
- As a **fan**, I want to create posts so I can share my thoughts with the community.  
- As a **fan**, I want to like and comment on posts so I can interact with others.  
- As a **fan**, I want to join a category (e.g., Fan Art) so I only see content that interests me.  
- As a **fan**, I want to receive notifications for new posts in my favorite categories so I stay updated.  
- As a **fan**, I want to edit my profile so I can personalize my community presence.  

---

## 🔹 4. Technology Stack  

### Option A: Native Android (Kotlin + Jetpack Compose)  
- Language: **Kotlin**  
- UI: **Jetpack Compose**  
- Architecture: **MVVM (Model-View-ViewModel)**  
- Async: **Coroutines + Flow**  
- Dependency Injection: **Hilt**  
- Network: **Retrofit + Moshi (REST API)**  
- Backend: **Firebase Firestore + Firebase Storage**  
- Auth: **Firebase Auth** 

---

## 🔹 5. Project Timeline  

- **Week 1-2:** Topic selection, problem statement, feature list, initial design (Figma mockup)  
- **Week 3:** Topic presentation to lecturer  
- **Week 4-6:** Build authentication and basic UI (login/register, navigation)  
- **Week 7-8:** Implement posts feed and categories  
- **Week 9:** Add likes, comments, and profile page  
- **Week 10:** Connect REST API for events/news  
- **Week 11:** Implement notifications, finalize UI design  
- **Week 12:** Testing, bug fixing, improve UX  
- **Week 13:** Final presentation and demo  

---

## 🔹 6. Version Control  
- Repository hosted on **GitHub**  
- Branching strategy: `main`, `dev`, `feature/*`  
- Commit history with meaningful messages  

--- 
