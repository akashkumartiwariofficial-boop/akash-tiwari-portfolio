# 🚀 Akash Tiwari | Portfolio & Interactive Cyber Hub

[![React 19](https://img.shields.io/badge/React-19.0-61DAFB?logo=react&logoColor=black)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-7.0-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS v4](https://img.shields.io/badge/TailwindCSS-v4.0-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Vite](https://img.shields.io/badge/Vite-8.3-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![Node.js / Express](https://img.shields.io/badge/Express-4.21-000000?logo=express&logoColor=white)](https://expressjs.com/)
[![Google Gemini API](https://img.shields.io/badge/Gemini_AI-2.4-8E75B2?logo=googlegemini&logoColor=white)](https://ai.google.dev/)

Official personal portfolio, research archive, and interactive cyber terminal of **Akash Tiwari** — Computer Science & Engineering, AI, and Cybersecurity specialist at **IIT Patna**, and Author of *"The Civic Sense of Indian People"*.

 Web link = https://akash-kumar-tiwari.netlify.app/
     
📍 **Location:** Patna, Bihar, India 
   

---

## ✨ Key Features

- **💻 Interactive Cyber Terminal CLI:** Full-screen hacker terminal with custom commands (`help`, `about`, `skills`, `projects`, `book`, `contact`, `clear`, `matrix`, `sudo`, `quote`).
- **📸 Dynamic Photo Gallery & Admin Portal:** 
  - Real-time photo gallery with category filters (Formal, Campus, Research, Events, Custom).
  - Built-in Admin Portal protected by PIN/Password authentication.
  - Complete CRUD functionality for photos (Upload, Edit details, Set featured main portrait, Delete, Sync with server storage).
- **📚 Published Work & Literature Showcase:** Highlighted section for *"The Civic Sense of Indian People"* with chapter excerpts and reader engagement.
- **🛡️ Cybersecurity & AI Project Catalog:** Categorized repository of active projects, research papers, patents, and technical expertise in AI/ML, Offensive Security, Systems, and Web3.
- **📄 Dynamic CV / Resume Hub:** Modal preview of full academic resume with direct print/download capabilities.
- **✉️ Direct Contact Gateway:** Interactive contact form powered by Express backend API.
- **🎨 Modern Cyberpunk Tech Design:** Custom typography featuring `Outfit`, `Space Grotesk`, `JetBrains Mono`, and `Noto Sans Devanagari` with ultra-smooth animations and dark mode aesthetics.

---

## 🛠️ Tech Stack

### **Frontend**
- **Framework:** React 19 + TypeScript
- **Build Tool:** Vite 8.3
- **Styling:** Tailwind CSS v4 + Custom Utility Layers
- **Icons:** Lucide React (`lucide-react`)
- **Animations:** Motion (`motion`)

### **Backend & API**
- **Server:** Express.js running on Node.js / `tsx` runner
- **AI Integration:** `@google/genai` (Google Gemini SDK)
- **Email Service:** Nodemailer
- **Persistence:** Local JSON file store + base64 image asset handlers

---

## 📁 Folder Structure

```text
akash-tiwari-portfolio/
├── src/
│   ├── assets/             # Static images, portraits, & book covers
│   ├── components/         # React Components
│   │   ├── AdminPortalPage.tsx  # Admin Portal for photo & site content management
│   │   ├── CVResumeModal.tsx    # Interactive resume modal & print view
│   │   ├── GalleryPage.tsx      # Public photo gallery with filtering
│   │   ├── TerminalModal.tsx    # Interactive CLI hacker terminal
│   │   ├── Header.tsx           # Navigation bar
│   │   └── Footer.tsx           # Site footer & contact info
│   ├── data/               # Static data, custom JSON, & gallery photos
│   │   ├── portfolioData.ts     # Main personal details, skills, & projects
│   │   ├── custom-portfolio.json # Overridable site configuration
│   │   └── gallery-data.json    # Photo gallery data store
│   ├── App.tsx             # Main App layout & route management
│   ├── main.tsx            # Entry point
│   └── index.css           # Global typography & Tailwind CSS directives
├── server.ts               # Express backend API server
├── index.html              # HTML entry point with Google Fonts
├── package.json            # Dependencies & build scripts
├── vite.config.ts          # Vite configuration
└── README.md               # Documentation
