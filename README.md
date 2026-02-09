<p align="center">
  <h1 align="center">next_login_page</h1>
  <p align="center">
    A Next.js login page demo showcasing React Hook Form validation, Chakra UI component variants, and Storybook-driven development.
  </p>
</p>

<p align="center">
  <a href="https://github.com/girijashankarj/next_login_page"><img src="https://img.shields.io/github/last-commit/girijashankarj/next_login_page?style=flat-square&logo=github" alt="last commit" /></a>
  <img src="https://img.shields.io/badge/Next.js-14-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js 14" />
  <img src="https://img.shields.io/badge/Chakra_UI-2.8-319795?style=flat-square&logo=chakraui&logoColor=white" alt="Chakra UI" />
  <img src="https://img.shields.io/badge/React_Hook_Form-7-EC5990?style=flat-square&logo=reacthookform&logoColor=white" alt="React Hook Form" />
  <img src="https://img.shields.io/badge/Storybook-7.5-FF4785?style=flat-square&logo=storybook&logoColor=white" alt="Storybook" />
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" alt="PRs welcome" />
</p>

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Quick Start](#quick-start)
- [Project Structure](#project-structure)
- [Scripts Reference](#scripts-reference)
- [Storybook](#storybook)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

**next_login_page** is a demo application that combines Next.js 14, Chakra UI, React Hook Form, and Storybook to build a production-quality login page. It demonstrates reusable form components with multiple input/button variants, form validation, and component documentation via Storybook.

---

## Features

- **Login form** — email and password fields with validation
- **React Hook Form** — performant form handling with error messages
- **Chakra UI variants** — outline, unstyled, flushed, filled inputs
- **Button variants** — solid, outline, ghost, link buttons
- **Storybook** — component isolation and documentation
- **Responsive design** — mobile-friendly layout
- **Reusable components** — custom input, button, form foundations

---

## Tech Stack

|                  | Details                              |
| ---------------- | ------------------------------------ |
| **Framework**    | Next.js 14                           |
| **UI Library**   | Chakra UI 2.8                        |
| **Forms**        | React Hook Form 7.47                 |
| **Component Dev**| Storybook 7.5                        |
| **Styling**      | Tailwind CSS 3.3 + Chakra theme      |
| **Language**      | React 18, JavaScript (JSX)           |
| **Linting**      | ESLint (Next.js config)              |

---

## Quick Start

```bash
git clone https://github.com/girijashankarj/next_login_page.git
cd next_login_page
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Run Storybook

```bash
npm run storybook
```

Open [http://localhost:6006](http://localhost:6006) to browse components.

---

## Project Structure

```
next_login_page/
├── src/
│   ├── app/
│   │   ├── foundations/            # Reusable components
│   │   │   ├── controlled-input-group/
│   │   │   ├── cust-button/
│   │   │   ├── cust-form/
│   │   │   ├── cust-input/
│   │   │   └── login-page/
│   │   ├── globals.css
│   │   ├── layout.js
│   │   ├── page.js
│   │   └── providers.js           # Chakra UI provider
│   └── stories/                    # Storybook stories
├── .storybook/                     # Storybook configuration
├── .github/workflows/              # CI/CD workflows
├── docs-build/                     # Built Storybook docs
├── next.config.js
├── tailwind.config.js
├── postcss.config.js
├── package.json
└── README.md
```

---

## Scripts Reference

| Script            | Command                           | Description                     |
| ----------------- | --------------------------------- | ------------------------------- |
| `dev`             | `next dev`                        | Start Next.js dev server        |
| `build`           | `next build`                      | Build for production            |
| `start`           | `next start`                      | Start production server         |
| `lint`            | `next lint`                       | Run ESLint                      |
| `storybook`       | `storybook dev -p 6006`           | Start Storybook dev server      |
| `build-storybook` | `storybook build -o docs-build`   | Build static Storybook          |

---

## Storybook

Storybook is configured for component development and documentation. It provides:

- **Component isolation** — develop and test components in isolation
- **Multiple variants** — preview all Chakra UI input/button variants
- **Interactive controls** — adjust props in real-time
- **Documentation** — auto-generated component docs

---

## Contributing

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b feature/my-feature`
3. **Make** your changes
4. **Commit** and open a Pull Request

---

## License

This project is open source. See the [LICENSE](LICENSE) file for details.

---

<p align="center">
  Built with discipline by <a href="https://github.com/girijashankarj">GarryTJ</a>
</p>
