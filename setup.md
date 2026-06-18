# setup.md

## Purpose

Create a consistent React frontend foundation.

This workflow prioritizes efficient execution and repeatable project setup.

Use established installation procedures whenever possible instead of repeatedly researching the same setup steps.

Focus reasoning and effort on project-specific decisions rather than routine dependency installation and configuration.

---

## Project Reference

Use the project folder name as the project reference.

If the project folder name cannot be determined, ask the user for it.

---

## Questions

Ask the user to choose an icon library.

Default: Lucide React

Options:

* Lucide React
* Heroicons
* React Icons
* Phosphor Icons

Ask the user to choose an animation library.

Default: Motion for React

Options:

* Motion for React
* GSAP
* Three.js
* None

---

## Create the Project

Create a Vite React TypeScript project in the current project folder using the project reference.

```bash
npm create vite@latest . -- --template react-ts
npm install
```

---

## Environment Configuration

Create a `.gitignore` file.

Create a `.env` file.

Ensure `.env` is included in `.gitignore`.

---

## Create .htaccess

Create a standard React Router Apache rewrite configuration.

---

## Install Tailwind CSS

```bash
npm install tailwindcss @tailwindcss/vite
```

Update `vite.config.ts`.

```ts
import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'
import tailwindcss from '@tailwindcss/vite'

export default defineConfig({
  plugins: [
    react(),
    tailwindcss(),
  ],
})
```

Import Tailwind in the main CSS file.

```css
@import "tailwindcss";
```

---

## Install React Router

```bash
npm install react-router-dom
```

---

## Install the Selected Icon Library

Lucide React

```bash
npm install lucide-react
```

Heroicons

```bash
npm install @heroicons/react
```

React Icons

```bash
npm install react-icons
```

Phosphor Icons

```bash
npm install @phosphor-icons/react
```

---

## Install the Selected Animation Library

Motion for React

```bash
npm install motion
```

GSAP

```bash
npm install gsap
```

Three.js

```bash
npm install three @react-three/fiber @react-three/drei
```

None

Skip installation.

---

## Verify

```bash
npm run dev
```

Confirm the project was created and is running successfully.

---

## Completion

Confirm the setup is complete.

After confirmation, continue to `smb-skills/smb-design.md`.
