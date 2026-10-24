# JeevikaAI - Voice-First Livelihood & Skill Guidance Platform

> **Multilingual voice-first livelihood and NSQF-aligned skill guidance platform designed for first-time digital users in Hindi, Bhojpuri, and English.**

---

## 🌟 Overview

**JeevikaAI** is an AI-powered, voice-first platform tailored for rural and semi-urban job seekers, artisans, daily-wage workers, and micro-entrepreneurs. It bridges the digital literacy divide through conversational voice interaction, dialect understanding, hyperlocal opportunity matching, and NSQF skill certification pathways.

---

## 🚀 Key Features

- 🎙️ **Voice-First Interaction**: Conversational AI assistant supporting Hindi, Bhojpuri, and English with real-time speech-to-text and voice playback.
- 🎯 **NSQF-Aligned Skill Guidance**: Assessment and roadmap recommendations aligned with National Skills Qualifications Framework standards.
- 📍 **Hyperlocal Opportunity Discovery**: Interactive map and district-level matching for training centers, government schemes, and job opportunities.
- 📱 **Progressive Web App (PWA)**: Installable, lightweight, and works seamlessly even on low-bandwidth mobile devices.
- 📊 **Admin CMS & Analytics**: Verification and management dashboard for tracking training partners, job openings, and user outcomes.
- 📄 **Resume & Skill Summary Export**: Generates printable and shareable skill summaries (PDF/image) for beneficiaries.

---

## 🛠️ Tech Stack

- **Frontend**: React 19, TypeScript, Tailwind CSS, Motion, Lucide Icons, Leaflet
- **Backend / Server**: Node.js, Express, TSX
- **AI & Speech**: Google GenAI SDK (`@google/genai`), Web Speech API, Custom Speech & Vocabulary Engines
- **Database / Auth**: Firebase / Cloud Firestore
- **Build & PWA**: Vite, `vite-plugin-pwa`

---

## 📦 Getting Started

### Prerequisites

- Node.js (version 20 or higher)
- npm or bun

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/2110774/jeevikaAi.git
   cd jeevikaAi
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up Environment Variables:**
   Copy `.env.example` to `.env` and fill in the necessary API keys:
   ```bash
   cp .env.example .env
   ```

4. **Run Development Server:**
   ```bash
   npm run dev
   ```

5. **Build for Production:**
   ```bash
   npm run build
   ```

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
