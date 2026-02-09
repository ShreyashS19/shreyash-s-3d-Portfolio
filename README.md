
# 🚀 Shreyash’s 3D  Portfolio

A modern, immersive **3D developer portfolio** built with **React, TypeScript, Three.js**, and **Tailwind CSS**, showcasing projects, skills, and interactive visualizations through animated 3D scenes.

This project combines **web performance**, **clean UI/UX**, and **real-time 3D rendering** to deliver a visually engaging personal website.

---

## 📑 Table of Contents

* [Overview](#-overview)
* [Live Preview](#-live-preview)
* [Features](#-features)
* [Tech Stack](#-tech-stack)
* [Project Structure](#-project-structure)
* [Installation](#-installation)
* [Usage](#-usage)
* [3D Scenes & Modules](#-3d-scenes--modules)
* [Configuration](#-configuration)
* [Testing](#-testing)
* [Performance & Optimization](#-performance--optimization)
* [Deployment](#-deployment)
* [Troubleshooting](#-troubleshooting)
* [Contributing](#-contributing)
* [License](#-license)

---

## 🌟 Overview

This portfolio is designed as a **3D storytelling experience** rather than a traditional static website.

It includes:

* Interactive **Three.js scenes** for projects
* Smooth animations using **Framer Motion**
* Responsive design with **Tailwind CSS**
* Modular and scalable **React + TypeScript** architecture
* Clean UI components powered by **shadcn/ui**

---

## 🔗 Live Preview

> 🚧 Replace with your deployed URL once live

```txt
https://your-portfolio-url.com
```

---

## ✨ Features

* 🌌 Interactive 3D hero background
* 🧠 Project-specific 3D visualizations (Finance, ML, Healthcare, SaaS)
* 🎨 Modern glassmorphism UI
* 📱 Fully responsive (desktop & mobile)
* ⚡ Fast builds with Vite
* 🧩 Reusable component architecture
* 🧪 Unit testing with Vitest
* 🌙 Dark-mode optimized design

---

## 🛠 Tech Stack

### Frontend

* **React 18**
* **TypeScript**
* **Vite**

### 3D & Animation

* **Three.js**
* **@react-three/fiber**
* **@react-three/drei**
* **Framer Motion**

### Styling & UI

* **Tailwind CSS**
* **shadcn/ui**
* **Radix UI**
* **Lucide Icons**

### State & Utilities

* **TanStack Query**
* **React Router DOM**
* **Zod**
* **React Hook Form**

### Testing & Tooling

* **Vitest**
* **ESLint**
* **PostCSS**

---

## 📂 Project Structure

```txt
reflex3334-shreyash-s-3d-journey/
├── public/
├── src/
│   ├── components/
│   │   ├── 3d/              # All Three.js scenes
│   │   ├── sections/        # Page sections (Hero, About, Projects, etc.)
│   │   ├── ui/              # shadcn UI components
│   ├── hooks/               # Custom React hooks
│   ├── pages/               # Route pages
│   ├── lib/                 # Utility functions
│   ├── test/                # Unit tests
│   ├── App.tsx
│   └── main.tsx
├── tailwind.config.ts
├── vite.config.ts
├── package.json
└── README.md
```

---

## ⚙️ Installation

### Prerequisites

* **Node.js ≥ 18**
* **npm** or **pnpm**

### Steps

```bash
# Clone repository
git clone <your-repo-url>

# Navigate to project
cd reflex3334-shreyash-s-3d-journey

# Install dependencies
npm install

# Start development server
npm run dev
```

---

## ▶️ Usage

* Open browser at:

```txt
http://localhost:8080
```

* Scroll to explore sections:

  * Hero (3D animated background)
  * About
  * Skills (interactive orbit)
  * Projects (3D visual demos)
  * Contact

---

## 🧊 3D Scenes & Modules

Each project has a **dedicated 3D scene**:

| Scene                  | Purpose                         |
| ---------------------- | ------------------------------- |
| `HeroScene`            | Landing page 3D background      |
| `BankSimulatorScene`   | Finance / Banking visualization |
| `ChurnPredictionScene` | ML analytics visualization      |
| `HospitalScene`        | Healthcare workflow demo        |
| `PlantDiseaseScene`    | AI & agriculture                |
| `ServiceHubScene`      | SaaS platform                   |
| `SkillsOrbit`          | Rotating skill planets          |

All scenes are built with **React Three Fiber** and optimized for performance.

---

## 🔧 Configuration

### Environment

No environment variables required by default.

### Tailwind

Modify:

```ts
tailwind.config.ts
```

### Vite

Modify:

```ts
vite.config.ts
```

---

## 🧪 Testing

Run unit tests:

```bash
npm run test
```

Watch mode:

```bash
npm run test:watch
```

---

## 🚀 Performance & Optimization

* Lazy-loaded 3D scenes
* Viewport-based rendering
* GPU-optimized materials
* Reduced draw calls
* Vite SWC compiler for fast builds

---

## 🌍 Deployment

### Recommended Platforms

* **Vercel**


Build command:

```bash
npm run build
```

Preview build:

```bash
npm run preview
```

---

## 🐛 Troubleshooting

| Issue        | Fix                  |
| ------------ | -------------------- |
| White screen | Check WebGL support  |
| 3D lag       | Reduce DPR in Canvas |
| Build errors | Ensure Node ≥ 18     |

---

## 📄 License

This project is licensed under the **MIT License**.

---


//change the folder name
  name the repo correct in github
  host oon versel