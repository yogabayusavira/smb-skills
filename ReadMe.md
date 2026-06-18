# SMB-skills

[![Vite](https://img.shields.io/badge/Vite-React-blue)](#)
[![TypeScript](https://img.shields.io/badge/TypeScript-Enabled-blue)](#)
[![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-Enabled-38B2AC)](#)
[![React Router](https://img.shields.io/badge/React_Router-Enabled-red)](#)

[![Ko-fi](https://img.shields.io/badge/Support-Ko--fi-ff5f5f?logo=ko-fi\&logoColor=white)](https://ko-fi.com/lifeonm_rs)
[![Community](https://img.shields.io/badge/Join-Whop_Community-5E17EB?logo=whop&logoColor=white)](https://www.whop.com/coalition)

Build professional local business websites with AI while minimizing token usage, reducing unnecessary AI reasoning, and avoiding SaaS-style design patterns.

## Getting Started

Open setup.md and follow the instructions there. That's the only file you need to begin. Everything else follows from it.

## Tech Stack

The core stack is **Vite, React, TypeScript, Tailwind CSS, and React Router**. For icons, the default is **Lucide React, with Heroicons, React Icons, and Phosphor Icons** available as alternatives. For animation, the default is **Motion for React, with GSAP and Three.js** available depending on project needs.

## Workflow

The system is designed to be followed in order. You start with setup.md to scaffold the project, then move to smb-skills/smb-design.md to define the layout and design system. From there you apply any relevant addons, check todo.md for outstanding items, implement required integrations, apply branding via smb-skills/branding.md, and finish with smb-skills/finalize.md for launch readiness.

## Folder Structure

```text
README.md
setup.md
todo.md

smb-skills/
├── smb-design.md
├── branding.md
├── finalize.md
├── addons/
└── integrations/
```

## What This System Solves

AI website builders tend to default to SaaS and software-product layouts. Local business websites have different goals. Visitors are usually trying to contact a business, request a quote, schedule a service, verify trust, or confirm availability — not evaluate a product. This system gives AI the context it needs to produce layouts designed for that intent instead of defaulting to startup-style pages.

## Core Files

### setup.md

Creates the project foundation — Vite React TypeScript, Tailwind, React Router, icon and animation library setup, environment configuration, and .htaccess.

### smb-design.md

Defines the full website structure including homepage, services, about, contact, navigation, reviews, service areas, forms, typography, images, and colors.

### branding.md

Handles logo, colors, images, favicon, and social sharing image.

### finalize.md

The launch checklist covering SEO metadata, Open Graph tags, sitemap, robots.txt, canonical URLs, accessibility, mobile responsiveness, and performance.

## Addons and Integrations

Addons provide optional functionality on top of the base site. Current addons include conversion-homepage.md, review-management.md, and pop-up-promo.md.

When an addon requires an external service, the corresponding integration file handles the setup — for example connect-openrouter.md, connect-resend.md, or connect-google-maps.md.

Integrations are only implemented when a required addon calls for them.

## Todo System

todo.md is the source of truth for anything unfinished. Whenever a requirement, dependency, integration, asset, credential, or feature is missing during the workflow, it gets appended there. No duplicate tasks.

## Design Principles

The system is mobile-first and built around trust over impressiveness, clarity over cleverness, and making it easy for visitors to contact or book the business. SaaS design patterns are avoided unless the business itself is a software product.

## Support

If this project helps you, consider starring the repository. It helps more people find it and supports continued development.
