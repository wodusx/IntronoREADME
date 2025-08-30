<p align="center">
  <picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/logo.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/logo_blue.png">
  <img alt="Logo" src="assets/logo_blue.png" width="120">
</picture>
</p>

<h1 align="center">Intranet for E-commerce Companies</h1>

<p align="center">
  A fullstack demo project built with <b>Next.js 15, Prisma, Supabase, NextAuth, Cloudinary, and shadcn/ui</b>.
  <br />
  <a href="https://introno-demo.vercel.app/" target="_blank"><strong>🔗 Live Demo</strong></a> (password-protected)
  <br />
  <sub>Request access via email or LinkedIn</sub>
</p>


## ✨ Features
- 📂 Folder & department-based access control
- 📝 Rich text editor for creating detailed work instructions (Tiptap + Cloudinary)
- 🔢 Step-by-step instruction builder (with attachments, no rich text)
- 🔒 Authentication with NextAuth (JWT sessions, Google login)
- 📊 Infinite scroll & advanced search for logs/news
- 🧑‍💼 User management with skill-based filtering (e.g., find employees by their competencies)
- ✅ Robust form validation using Zod
- 🎨 Modern UI with shadcn/ui & Tailwind


## 🔒 Security
- 🚫 **SQL Injection protection** – all database queries are handled via Prisma ORM
- 🛡️ **CSRF protection** – NextAuth handles anti-CSRF tokens automatically during authentication
- ✋ **Rate limiting** on API endpoints to prevent brute-force attacks
- 🧼 **XSS protection** – user input sanitized and validated with Zod; rich text editor restricted to safe HTML
- 🔑 **Secure sessions** – JWT-based sessions with HttpOnly cookies
- 🔐 **Access control** – role- and department-based authorization for folders and instructions


## 🛠️ Tech Stack
- **Frontend**: Next.js 14, React, TypeScript, Tailwind, shadcn/ui
- **Backend**: Prisma ORM, MySQL (Supabase), NextAuth
- **Other**: Cloudinary (image storage), WeatherAPI (integration)


## 📸 Screenshots
<p align="center">
  <img src="https://your-screenshot-link1.png" alt="Dashboard Screenshot" width="700" />
</p>

<p align="center">
  <img src="https://your-screenshot-link2.png" alt="Editor Screenshot" width="700" />
</p>



