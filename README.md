# Product Development Cohort — June 2025

**Product Development Cohort — June 2025** is a full-stack web application built as part of a skill-building cohort project.  
This repo contains a frontend app built with **React + TypeScript + Vite + Tailwind CSS**, associated utilities, and some project artifacts (API bundles, demo project zips). The project was forked from **Abhiix0/Product-Development-Cohort-June-2025** and is organized to reflect an end-to-end product demo. :contentReference[oaicite:1]{index=1}

---

## 🚀 Key Features

✔ Modern frontend architecture using React with TypeScript  
✔ Structured component, hook, and library layers  
✔ Tailwind CSS for utility-first styling  
✔ Separate directories for *app*, *src*, and reusable modules  
✔ Includes demo artifacts and build bundles (API and sample apps)

---

## 🗂 Project Structure

```

Product-Development-Cohort-June-2025/
├── api/                   # API related files or backend bundles (zipped)
├── app/                   # App specific modules or routes
├── components/            # Shared UI components
├── hooks/                 # Custom React hooks
├── lib/                   # Utility libraries/helpers
├── models/                # TypeScript data models
├── project/               # Project assets/examples
├── public/                # Static assets
├── src/                   # Frontend source
├── styles/                # Global styles / Tailwind base
├── .gitignore
├── components.json
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
├── tsconfig.json
├── vite.config.ts
└── (lock files + demo zips e.g., api.zip, mlrit-court-booking.zip)

````

*TypeScript is the main language (~95%), with small amounts of CSS/JS/HTML. :contentReference[oaicite:2]{index=2}*

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | React |
| Language | TypeScript |
| Build Tool | Vite |
| Styling | Tailwind CSS |
| Tools | npm / pnpm |
| Artifacts | API zip bundles, sample project zips |

---

## 🧩 Prerequisites

Before running the project locally, install:

- **Node.js** (v16+ recommended)
- **npm** or **pnpm**
- (Optional) unzip tools to extract API or demo bundles

---

## 📦 Setup & Installation

1. **Clone the repository**

```bash
git clone https://github.com/Mahi11313/Product-Development-Cohort-June-2025.git
cd Product-Development-Cohort-June-2025
````

2. **Install dependencies**

```bash
npm install
```

*Or, if using pnpm:*

```bash
pnpm install
```

---

## 🧪 Run in Development

Start the local development server:

```bash
npm run dev
```

Open your browser and visit:

```
http://localhost:5173
```

*(Default Vite port — may differ if configured)*.

---

## 📦 Production Build

To generate a production-ready build:

```bash
npm run build
```

This produces an optimized `dist/` folder suitable for deployment.

---

## 🧠 How to Use / Extend

### Frontend

* **Components:** Add reusable UI parts in `components/`
* **Hooks:** Manage custom logic in `hooks/`
* **Models:** Define consistent TypeScript types/interfaces in `models/`
* **App Logic:** Refactor or extend features in `app/` and `src/`

### Backend/Artifacts

* **API Bundles:** Extract and deploy API functions from `api.zip`
* **Demo Apps:** Use sample zips (e.g., `mlrit-court-booking.zip`) for demonstration or testing.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m "feat: Add something awesome"`)
4. Push to your fork (`git push origin feature-name`)
5. Open a pull request

---
