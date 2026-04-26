<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/b1cd12ff-9d63-4a2a-973b-a1883f8e6922

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`
   # 🔬 LabShare – Research Equipment Sharing Platform

A full-stack web platform that enables different departments to share specialized research equipment efficiently. Researchers can request access, track usage, and manage approvals through a centralized system.
## 🚀 Features
* 🔐 **User Authentication System**
* 🏢 **Department-based Equipment Listing**
* 📅 **Equipment Booking & Scheduling**
* ✅ **Approval Workflow System**
* 📊 **Usage Logs for Accountability**
* 🤖 **AI Integration (Google GenAI)**
* ⚡ **Fast Frontend using Vite + React**
* 🎨 **Modern UI with Tailwind CSS**
## 🛠️ Tech Stack
### Frontend
* React (Vite)
* TypeScript
* Tailwind CSS
### Backend
* Node.js
* Express.js
* TypeScript
### Database
* MongoDB (via MONGODB_URI)
### Other Tools
* @google/genai
* TanStack React Query
* ESBuild
## 📁 Project Structure
LabShare-main/
│── server/              # Backend logic
│── src/                 # Frontend source
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── context/
│── .env.example         # Environment variables
│── package.json
│── vite.config.ts
│── server.ts
```
## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/labshare.git
cd labshare
### 2️⃣ Install dependencies

```bash
npm install
```
### 3️⃣ Setup environment variables

Create a `.env` file and add:

```env
MONGODB_URI=your_mongodb_connection_string---
### 4️⃣ Run the project
#### Development mode
```bash
npm run dev
```
#### Build project
```bash
npm run build
```
#### Start production server

```bash
npm start
## 🌐 Live Demo

👉 https://your-render-link.onrender.com

---## ⚠️ Important Note

If `MONGODB_URI` is not set, the backend will not connect to the database and some API features may fail.

---## 📸 Screenshots

*Add your screenshots here (Login Page, Dashboard, Equipment List, etc.)*

---<img width="1892" height="868" alt="Screenshot 2026-04-26 125859" src="https://github.com/user-attachments/assets/ccb48d3c-1d7b-4de6-8964-5bf18fbd4012"


## 🎯 Future Enhancements

* 🔔 Notification system for approvals
* 📱 Mobile responsiveness improvements
* 📈 Analytics dashboard
* 🔍 Advanced search & filters
* 🤝 Multi-role access (Admin, Researcher)

---

## 👩‍💻 Author

**Mehak**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
# 🔬 LabShare – Research Equipment Sharing Platform

A full-stack web platform that enables different departments to share specialized research equipment efficiently. Researchers can request access, track usage, and manage approvals through a centralized system.

---

## 🚀 Features

* 🔐 **User Authentication System**
* 🏢 **Department-based Equipment Listing**
* 📅 **Equipment Booking & Scheduling**
* ✅ **Approval Workflow System**
* 📊 **Usage Logs for Accountability**
* 🤖 **AI Integration (Google GenAI)**
* ⚡ **Fast Frontend using Vite + React**
* 🎨 **Modern UI with Tailwind CSS**

---

## 🛠️ Tech Stack

### Frontend

* React (Vite)
* TypeScript
* Tailwind CSS

### Backend

* Node.js
* Express.js
* TypeScript

### Database

* MongoDB (via MONGODB_URI)

### Other Tools

* @google/genai
* TanStack React Query
* ESBuild

---

## 📁 Project Structure

```
LabShare-main/
│── server/              # Backend logic
│── src/                 # Frontend source
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── context/
│── .env.example         # Environment variables
│── package.json
│── vite.config.ts
│── server.ts
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/labshare.git
cd labshare
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 4️⃣ Run the project

#### Development mode

```bash
npm run dev
```
#### Build project
```bash
npm run build
#### Start production server

```bash
npm start
## 🌐 Live Demo

👉 https://your-render-link.onrender.com
## 🎯 Future Enhancements
* 🔔 Notification system for approvals
* 📱 Mobile responsiveness improvements
* 📈 Analytics dashboard
* 🔍 Advanced search & filters
* 🤝 Multi-role access (Admin, Researcher)
* ## 👩‍💻 Author
**Mehak**
## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

