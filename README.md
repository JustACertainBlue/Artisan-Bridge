# 🌏 Artisan Bridge  
### A Digital Platform Connecting Travel Agencies with Craft Villages

---

## 📌 Overview

**Artisan Bridge** is a web-based platform designed to connect **travel agencies** with **traditional craft villages**, enabling them to collaboratively design, manage, and execute cultural tourism experiences.

The platform operates under the supervision of tourism authorities (e.g., Hanoi Department of Tourism) to ensure **quality control, authenticity, and sustainable tourism development**.

---

## 🎯 Problem Statement

Traditional craft villages face:
- Limited visibility to travel agencies  
- Inefficient, manual coordination processes  
- Lack of standardized contracts and communication tools  

Travel agencies struggle with:
- Discovering reliable local partners  
- Verifying quality and credibility  
- Managing collaboration workflows efficiently  

---

## 💡 Solution

Artisan Bridge provides a **centralized digital ecosystem** that enables:

- 🔍 Discovery of craft villages and cultural tours  
- 🤝 Partner matching between agencies and artisans  
- 📄 End-to-end **e-contract lifecycle management**  
- 💬 Real-time communication and negotiation  
- ⭐ Ratings and review system for trust-building  
- 🛠 Administrative governance for quality assurance  

---

## 🧩 Core Features

### 1. Account & Profile Management
- User registration, login, and authentication  
- Profile creation and management  
- Role-based access (Agency / Craft Village / Admin)

### 2. Directory & Tour Management
- Search and filter craft villages by location, category, and specialty  
- Browse and explore available tours  
- Craft villages can create, edit, and publish tour offerings  

### 3. E-Contract Management
- Auto-generated contract templates  
- Contract creation, editing, and negotiation  
- Finalization with digital signature support  

### 4. Communication & Interaction
- Real-time chat between travel agencies and craft villages  
- Notification system (in-app + email)  
- Rating and review system  

### 5. Administration Dashboard
- User approval and moderation  
- System analytics and monitoring  
- Partnership suggestion and quality control  

---

## 🏗 System Architecture

The system follows a **multi-layer architecture**:

### Presentation Layer
- Public landing page  
- User web portal (agencies & craft villages)  
- Admin dashboard  

### Business Layer
- Authentication & Authorization Service  
- Tour Management Service  
- E-Contract Engine  
- Communication Service  
- Admin Operations Service  

### External Services
- Google Maps API (geolocation & distance calculation)  
- Cloudinary (media storage & delivery)  
- SendGrid (email delivery system)  

### Persistence Layer
- Repository pattern for data access  
- Logging system for activity tracking  

### Database Layer
- **Structured Database**: Users, tours, contracts  
- **Unstructured Database**: Chat logs, activity logs  

---

## 🔄 Key Workflow

1. Travel agency searches for craft villages or tours  
2. Selects and sends a partnership request  
3. Creates and negotiates an e-contract  
4. Craft village reviews and accepts the contract  
5. Tour is executed  
6. Both parties provide ratings and feedback  

---
## 📁 Repository Structure
- [Architecture/](https://github.com/JustACertainBlue/Artisan-Bridge/tree/main/Architecture) – system design, diagrams, and technical flows
-[ Docs/](https://github.com/JustACertainBlue/Artisan-Bridge/tree/main/Docs) – project documentation and SRS
-[ UI.UX/](https://github.com/JustACertainBlue/Artisan-Bridge/tree/main/UI.UX) – user interface designs and user flows

## 🧑‍💻 Tech Stack (Proposed)

| Layer       | Technology                      |
|------------|--------------------------------|
| Frontend    | React / Next.js               |
| Backend     | Node.js / Express / Spring Boot |
| Database    | PostgreSQL + MongoDB          |
| Cloud       | AWS / Firebase                |
| APIs        | Google Maps API, SendGrid     |
| Media       | Cloudinary                    |

---

## 📊 Project Scale

- ~560 Function Points (medium-to-large system)  
- Multi-actor system:
  - Travel Agencies  
  - Craft Villages  
  - Government Admin  

---

## 🚀 Future Improvements

- AI-based partner recommendation system  
- Smart tour suggestions based on user behavior  
- Integrated booking and payment system  
- Mobile application (iOS / Android)  
- Data analytics dashboard for tourism insights  

---
