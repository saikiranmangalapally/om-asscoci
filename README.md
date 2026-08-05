# 🏛️ OM CA and Law Firm — Corporate CA & Legal Platform

[![Next.js](https://img.shields.io/badge/Next.js-16.3.0-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.0-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Vercel Deployment](https://img.shields.io/badge/Vercel-Ready-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)

A modern, high-converting Chartered Accountancy & Corporate Advisory web application engineered for **OM CA and Law Firm**. Built with Next.js 16 (App Router), TypeScript, Framer Motion, and Tailwind CSS.

---

## ⚡ Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/your-username/om-ca-and-law-firm.git

# 2. Navigate to project directory
cd om-ca-and-law-firm

# 3. Install dependencies
npm install

# 4. Start local development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🚀 One-Click Vercel Deployment

Deploy this project directly to **Vercel** with zero configuration required:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fyour-username%2Fom-ca-and-law-firm)

---

## 📁 Repository Structure

```
om-ca-and-law-firm/
├── .github/
│   └── workflows/
│       └── ci.yml               # GitHub Actions CI Workflow
├── public/                      # Static assets (favicons, og-images)
├── src/
│   ├── app/                     # Next.js 16 App Router pages & API routes
│   │   ├── [slug]/              # 60+ Dynamic Service Pages
│   │   ├── api/                 # Serverless API Endpoints (contact form & rate-limiting)
│   │   │   └── contact/
│   │   ├── about-us/            # About Us Page
│   │   ├── blog/                # Compliance Knowledge Hub
│   │   ├── contact-us/          # Contact Page
│   │   ├── layout.tsx           # Root Layout with Font & SEO metadata
│   │   └── page.tsx             # Homepage Canvas
│   ├── components/              # Modular UI Components
│   │   ├── common/              # Reusable Icons & Buttons
│   │   ├── home/                # Hero Banner, Service Selector Hub, Testimonials
│   │   ├── layout/              # Header, BrandLogo, Footer, MegaMenu, MobileMenu
│   │   └── service/             # Dynamic Service Page Templates
│   ├── data/                    # Service Data & Navigation Taxonomies
│   │   ├── navigation.ts
│   │   └── services.ts
│   ├── lib/                     # Rate Limiter & SEO Helper Utilities
│   │   ├── rateLimit.ts
│   │   └── seo.ts
│   └── middleware.ts            # Security HTTP Headers (CSP, X-Frame-Options)
├── .gitignore                   # Git Ignore Configuration
├── next.config.ts               # Next.js Production Configuration
├── package.json                 # Project Dependencies & Scripts
├── tsconfig.json                # TypeScript Configuration
└── vercel.json                  # Vercel Deployment Rules
```

---

## 🔒 Security & Reliability Audit Features
- **Rate Limiting**: Built-in token bucket rate-limiting on form endpoints (`HTTP 429` throttling).
- **HTTP Security Headers**: `X-Frame-Options: DENY`, `X-Content-Type-Options: nosniff`, `Content-Security-Policy`.
- **Input Sanitization**: Server-side regex validation on Indian mobile numbers and user input.

---

## 📄 License
© OM CA and Law Firm. All rights reserved.
