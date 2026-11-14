# 💊 MedicinAI - Intelligent Medication & Pharmacy Assistant

[![React](https://img.shields.io/badge/React-18.3-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.5-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Supabase](https://img.shields.io/badge/Supabase-Database%20%26%20Auth-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com/)
[![Zustand](https://img.shields.io/badge/Zustand-State%20Management-764ABC?style=for-the-badge)](https://zustand-demo.pmnd.rs/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

**MedicinAI** is a healthcare and pharmacy management web platform designed to streamline prescription workflows, provide AI-assisted medicine guidance, maintain offline-accessible medication schedules, and generate clinical PDF reports.

---

## ✨ Features

- 🤖 **Smart Medicine Insights:** AI-driven interaction warnings and dosage advisory.
- 🗄️ **Cloud & Offline Sync:** Powered by **Supabase** for secure remote data and **Dexie.js (IndexedDB)** for local, offline-first reliability.
- 📄 **Prescription & Report Generation:** Built-in PDF export utilities powered by `jspdf`.
- ⚡ **Lightweight State Management:** Ultra-fast reactive store built with **Zustand**.
- 🔒 **Type-Safe Validation:** Strict schema validation with **Zod** and TypeScript.
- 🎨 **Responsive Health UI:** Built with Tailwind CSS and Headless UI for an accessible user experience.

---

## 🛠️ Tech Stack

- **Frontend:** React 18, Vite 5, TypeScript
- **Styling:** Tailwind CSS, Headless UI, Lucide Icons
- **State & Offline Storage:** Zustand, Dexie.js (IndexedDB)
- **Backend & Cloud:** Supabase (PostgreSQL & Auth), Google APIs
- **Validation & Utilities:** Zod, date-fns, jsPDF, crypto-js

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v18+)
- npm or yarn
- Supabase project credentials

### Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Arbaz14/medicinai.git
   cd medicinai
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Configure Environment Variables:**
   Create a `.env` file from `.env.example`:
   ```env
   VITE_SUPABASE_URL="your-supabase-url"
   VITE_SUPABASE_ANON_KEY="your-supabase-anon-key"
   ```

4. **Launch Development Server:**
   ```bash
   npm run dev
   ```

5. **Build for Production:**
   ```bash
   npm run build
   ```

---

## 👨‍💻 Author

**Arbaz Khan**  
- GitHub: [@Arbaz14](https://github.com/Arbaz14)  
- Role: Full Stack MERN & Web Application Developer
