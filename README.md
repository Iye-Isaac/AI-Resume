# AI Resume Analyzer

<div align="center">
  <a href="https://www.youtube.com/watch?v=iYOz165wGkQ" target="_blank">
    <img src="public/readme/hero.webp" alt="Project Banner" />
  </a>

  <div>
    <img alt="React" src="https://img.shields.io/badge/React-4c84f3?style=for-the-badge&logo=react&logoColor=white">
    <img alt="Tailwind" src="https://img.shields.io/badge/-Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
    <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logoColor=white&color=3178C6" />
    <img alt="Puter.js" src="https://img.shields.io/badge/Puter.js-181758?style=for-the-badge&logoColor=white">
  </div>

  <h3 align="center">AI Resume Analyzer</h3>
  <p align="center">A lightweight, client-side app that analyzes resumes, scores them against job listings, and gives actionable feedback using modern browser AI & storage tools.</p>
</div>

---

## 📋 Table of Contents

1. ✨ [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🔗 [Assets](#links)
6. 🚀 [More](#more)

---

## ✨ Introduction

This is my personal AI Resume Analyzer — a single-page app built with React and TypeScript. It lets users upload resumes, store them securely in the browser, and run AI-assisted evaluations against job descriptions to produce ATS-style scores and tailored feedback. I built it to prototype a fast, privacy-first candidate screening workflow without needing a backend.

---

## ⚙️ Tech Stack

- **React** — component-driven UI for fast iteration.  
- **React Router v7** — route management and nested views.  
- **Puter.js** — serverless auth, storage, and AI capabilities directly in the browser.  
- **Tailwind CSS** — utility-first styling for a clean responsive UI.  
- **TypeScript** — type-safe code and better dev tooling.  
- **Vite** — fast dev server and build pipeline.  
- **Zustand** — small, efficient global state store.

---

## 🔋 Features

- **Client-side auth & storage** — sign-in and resume storage handled securely in the browser.  
- **Resume upload & management** — upload multiple resumes, store and retrieve them easily.  
- **AI resume matching** — paste a job listing and get an ATS-style score with specific feedback.  
- **ATS feedback & suggestions** — rewrite prompts and improvement tips tailored to each job.  
- **Reusable UI components** — modular, production-ready components to speed feature additions.  
- **Responsive design** — works smoothly on desktop and mobile.

---

## 🤸 Quick Start

Get this project running locally:

**Prerequisites**

- Git  
- Node.js  
- npm or yarn

**Clone & Install**

```bash
git clone https://github.com/your-username/ai-resume-analyzer.git
cd ai-resume-analyzer
npm install
