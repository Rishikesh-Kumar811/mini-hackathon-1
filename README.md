<div align="center">

# ⚡ FinTrack Mini — React 19 + Redux Toolkit Financial Dashboard & 🌐 Live Demo

**A high-velocity, reactive financial management web application built with React 19, Redux Toolkit state architecture, Tailwind CSS, and Vite featuring micro-animated transaction controls and real-time ledger metrics.**

<br/>

<a href="https://www.rishifintrack.dev/" target="_blank"><img src="https://img.shields.io/badge/LIVE_DEMO-FINTRACK_MINI-0070F3?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo" /></a>&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://github.com/Rishikesh-Kumar811/mini-hackathon-1" target="_blank"><img src="https://img.shields.io/badge/GITHUB-REPOSITORY-24292e?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repository" /></a>

<br/><br/>

</div>

---

## 🛠️ Tech Stack

<br/>

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,redux,vite,tailwind,js,html,css,vercel,vscode,git,github" alt="Tech Stack" />
</p>

<br/>

| Layer | Technologies & Modern Standards | Implementation in Codebase |
| :--- | :--- | :--- |
| **UI Framework** | **React 19** • Functional Components • Hooks | Modern component hierarchy (`DashboardStats`, `TransactionForm`, `TransactionList`, `AnimatedDeleteButton`), React hooks lifecycle, and modular UI structure. |
| **State Architecture** | **Redux Toolkit (`@reduxjs/toolkit`)** • Immer | Centralized global store (`store.js`), dedicated `transactionSlice.js`, type-safe reducers, and predictable immutable state updates. |
| **Styling & Icons** | **Tailwind CSS** • **PostCSS** • **Lucide Icons** | Utility-first styling pipeline, responsive flex/grid layouts, micro-interaction transitions, and scalable vector icons. |
| **Build & Tooling** | **Vite** • **Vercel** • **Git** • **GitHub** | Next-generation Vite bundler with instant Hot Module Replacement (HMR), PostCSS transformation, and Vercel edge hosting. |

<br/>

---

## ✨ Key Features

<br/>

### 1. 🔄 Centralized Redux State Management Pipeline
- **Predictable State Mutations**: Structured `transactionSlice` handling actions for adding, deleting, and updating financial line items.
- **Derived Financial Metrics**: Real-time selectors computing net balance, total credits, and total debits across the entire ledger.
- **Unidirectional Data Flow**: Strict decoupling of presentation components from state mutations ensuring clean architecture.

### 2. 🗑️ Animated Interactive Delete Confirmation UX
- **Micro-Interaction Polish**: Custom `AnimatedDeleteButton.jsx` providing visual feedback during destructive operations.
- **Accidental Deletion Prevention**: Built-in interactive confirmation states preventing accidental ledger modifications.
- **Hardware-Accelerated Transitions**: Smooth opacity and transform animations maintaining 120FPS rendering performance.

### 3. 🛡️ Resilient Component Error Boundary & Input Validation
- **Graceful Error Recovery**: Custom `ErrorBoundary.jsx` isolating UI runtime exceptions without crashing the full application tree.
- **Form Sanitization**: Dedicated `validation.js` utility ensuring non-empty titles, valid decimal amounts, and valid categories before dispatching actions.

### 4. 📈 Dynamic KPI Dashboard Statistics
- **Live Summary Cards**: Instant numerical visualizers for Current Balance, Inflow, and Outflow with dynamic conditional badge styling.
- **Real-Time Feed**: Responsive `TransactionList.jsx` rendering chronological entries with category badges and timestamps.

<br/>

---

## 📁 Project Directory Structure

<br/>

<details>
<summary><b>Click to expand project tree</b></summary>

```ascii
mini-hackathon-1/
├── index.html
├── package.json
├── package-lock.json
├── postcss.config.js
├── tailwind.config.js
├── vite.config.js
├── public/
│   ├── favicon.svg
│   └── icons.svg
├── src/
│   ├── App.jsx
│   ├── index.css
│   ├── main.jsx
│   ├── assets/
│   │   ├── hero.png
│   │   ├── react.svg
│   │   └── vite.svg
│   ├── components/
│   │   ├── AnimatedDeleteButton.jsx
│   │   ├── DashboardStats.jsx
│   │   ├── ErrorBoundary.jsx
│   │   ├── TransactionForm.jsx
│   │   ├── TransactionList.jsx
│   │   └── ui/
│   │       └── InputField.jsx
│   ├── redux/
│   │   ├── store.js
│   │   └── transactionSlice.js
│   └── utils/
│       └── validation.js
└── README.md
```

</details>

<br/>

---

## ⚡ Engineering Highlights

- **Modern React 19 Foundation**: Leverages the latest React paradigms for optimal component rendering.
- **Clean Redux Store Architecture**: Demonstrates clean separation of concerns and scalable state management.
- **Production-Ready Bundle**: Minified, tree-shaken asset bundle generated via Vite for instant web delivery.

<br/>

---

## 🚀 Quick Start & Local Setup

### 1. Clone the repository
```bash
git clone https://github.com/Rishikesh-Kumar811/mini-hackathon-1.git
cd mini-hackathon-1
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run development server
```bash
npm run dev
```

Visit `http://localhost:5173` in your web browser.

### 4. Build for production
```bash
npm run build
```

<br/>

---

## 👨‍💻 Author & Connect

| Developer | Portfolio / Profile | Live Platform |
| :--- | :--- | :--- |
| **Rishikesh Kumar** | [@Rishikesh-Kumar811](https://github.com/Rishikesh-Kumar811) | [FinTrack Mini Dashboard](https://www.rishifintrack.dev/) |

---

<div align="center">
  <sub>Engineered with precision by Rishikesh Kumar • 2026 Spec</sub>
</div>
