# ⚡ The Stack Fix

> **Fix Your Code. Build Your Skills.**
>
> A hybrid developer platform offering ad-free utilities, deep-dive articles, and live project architectures — built with **Next.js**, **TypeScript**, and **Tailwind CSS**.

---

## 🧩 Overview

**The Stack Fix** is a high-performance, developer-first web platform designed to help full-stack developers:

- Instantly access **micro-utilities** (JSON tools, regex testers, etc.)
- Read **in-depth engineering articles**
- Showcase **real-world project architectures**

All in one clean, distraction-free environment.

---

## 🚀 Tech Stack

| Layer | Technology | Purpose |
| :---- | :----------- | :-------- |
| **Frontend Framework** | [Next.js 14 (App Router)](https://nextjs.org/) | Server-side rendering, static site generation |
| **Language** | [TypeScript](https://www.typescriptlang.org/) | Type-safe, scalable code |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/) | Utility-first styling |
| **UI Library** | [shadcn/ui](https://ui.shadcn.com/) | Reusable modern UI components |
| **Markdown/Content** | [MDX + Contentlayer](https://contentlayer.dev/) | For blogs and structured content |
| **Hosting** | [Vercel](https://vercel.com/) | Lightning-fast edge deployment |

---

## 🧱 Project Structure

The Stack Fix follows a **modular, scalable structure** for maintainability and performance.

```
the-stack-fix/
├── public/                      # Static assets (icons, logos, etc.)
├── src/                         # Source code (renamed from 'web' for standardization)
│   ├── app/                     # Next.js routes and pages
│   ├── components/              # Reusable UI + layout components
│   │   ├── ui/                  # Buttons, Cards, Inputs, Modals
│   │   └── layouts/             # Page layouts (Home, Blog, Tools)
│   ├── data/                    # MDX articles, metadata, and SEO info
│   ├── tools/                   # Individual utility tools (JSON, Regex, etc.)
│   ├── lib/                     # Configs (Appwrite, Database, Utils)
│   ├── services/                # Serverless APIs and logic
│   └── styles/                  # Global styles & Tailwind directives
│
├── .env.local                   # Environment variables (not committed)
├── package.json                 # Dependencies and scripts
├── tsconfig.json                # TypeScript configuration
├── tailwind.config.ts           # Tailwind theme customization
└── README.md
```

---

## 🎨 UI/UX Philosophy

- **Minimal, fast, and distraction-free** interface
- Built with **zero images**, pure **SVGs**, and **sub-second load time**
- Clean typography using `Inter` or `Plus Jakarta Sans`
- **Dark Mode** by default for developer comfort
- Consistent two-panel layout for all tools (input → output)

---

## 🧠 Core Principles

1. **Developer-Centric:** Every page is designed to give instant utility.
2. **Ad-Free:** 100% clean UI — no popups, no clutter.
3. **Scalable:** Built for 50+ tools and 150+ blog articles.
4. **Transparent:** Open-source and community-friendly.

---

## 🧩 Roadmap

| Phase | Focus | Key Goals |
| :---- | :---- | :---- |
| **Phase 1** | MVP | Launch core utilities + 3 core blog categories |
| **Phase 2** | Engagement | Add email subscription, dark mode toggle |
| **Phase 3** | Quality | Add testing, error tracking, and improved UX |
| **Phase 4** | Scale | Introduce AI-powered code assist tools |

---

## 🛠️ Commands

### Run locally

```bash
npm install
npm run dev
```

### Build for production

```bash
npm run build
npm start
```

---

## 📬 Connect

Built with ❤️ by **Bablu Kumar**

- 🌐 [Portfolio Coming Soon](#)
- 🐙 [GitHub](#)
- 🧠 [LinkedIn](#)

⭐ **Star this repository if you believe in developer-first products.**
