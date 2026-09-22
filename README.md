# GigFlow ⚡
### Smart Invoicing & Real-Time Tax Estimator for Freelancers & Gig Workers

[![Vite](https://img.shields.io/badge/Vite-6.1-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![React](https://img.shields.io/badge/React-18.3-61DAFB?logo=react&logoColor=black)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.7-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-3.4-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**GigFlow** is a modern, high-conversion SaaS web application designed to solve the two biggest headaches in the global gig economy: **late client payments** and **tax anxiety**.

---

## 🌟 Key Features

- 💸 **"Safe-to-Spend" Metric**: Real-time formula (`Collected Revenue - Tax Withholding - Expenses`) showing true disposable income.
- 📄 **1-Click Clean PDF Invoices**: Pixel-perfect invoice generation with dedicated print styling (`@media print`) and zero external service dependencies.
- ⚡ **Embedded Payment Links**: Embedded Stripe checkout, PayPal.me, UPI QR/VPA (for Indian/Asian creators), and direct Bank Wire details right on the invoice.
- ⏰ **Automated Payment Nudge Engine**: Pre-filled, calibrated client payment reminders in 3 tones (Gentle, Due Today, Firm Overdue) with 1-click **WhatsApp** and **Email** dispatch.
- 🛡️ **Multi-Regime Tax Estimator**:
  - **US (1099 / Schedule C)**: 15.3% Self-Employment FICA tax + estimated federal bracket.
  - **India (Section 44ADA)**: 50% presumptive profit taxation rule + slab rates.
  - **UK (Sole Trader)**: Basic rate income tax + Class 4 National Insurance.
  - **Custom Flat %**: User-configurable percentage rate.
- 📉 **Deductible Expense Tracker**: Track software, hardware, office, and travel expenses to directly reduce tax obligations.
- 📊 **CPA / Tax Summary Export**: 1-click export to CSV for accountants.
- 👥 **Client Directory & Reliability Scores**: Track client punctuality (`⚡ Fast`, `🕒 Standard`, `⏳ Slow`).
- 💎 **Built-in $9/Month Pro Monetization Tier**: High-converting paywall model with Free vs. Pro feature gating.

---

## 🚀 Quick Start

### 1. Install Dependencies
```bash
npm install
```

### 2. Run Development Server
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser.

### 3. Build for Production
```bash
npm run build
```

---

## 🛠️ Tech Stack

- **Framework**: React 18 with Vite & TypeScript
- **Styling**: Tailwind CSS with custom FinTech palette & print layout
- **Icons**: Lucide React
- **Storage**: LocalStorage with automatic schema persistence

---

## 📄 License
MIT License. Built for independent professionals and creators worldwide.
