# B-PLAN Consulting — Strategic Business Solutions

B-PLAN Consulting delivers transformative business strategies and operational excellence. This repository contains the source for the professional marketing website, built with modern web technologies and optimized for high performance and visual excellence.

**Live Site**: [B-PLAN Consulting](https://b-plan-consulting.vercel.app/) (Deployed on Vercel)

## Project Overview

- **Purpose**: A premium marketing platform showcasing consulting services, industry insights, and corporate about/contact information.
- **Key Features**:
  - Interactive Service catalog
  - In-depth Industry Insights & Research articles
  - Careers portal and Team showcase
  - Dark-First Design for a professional, focused atmosphere
  - Responsive design for all devices

## Tech Stack

- **Framework**: [Vite](https://vitejs.dev/) + [React](https://reactjs.org/) + [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **UI Components**: [shadcn/ui](https://ui.shadcn.com/) (Radix UI + Lucid Icons)
- **Routing**: [React Router](https://reactrouter.com/) (using `HashRouter` for deployment compatibility)
- **Deployment**: [Vercel](https://vercel.com/)

## Project Structure

```text
src/
├── components/     # Shared UI components and shadcn primitives
├── hooks/          # Custom React hooks (theme, etc.)
├── lib/            # Utilities and Content Adapter (`content.ts`)
├── pages/          # Main application views
├── App.tsx         # Root component & Routing
└── index.css       # Design system and global styles
public/             # Static assets (logo, favicon)
scripts/            # Environment setup and developer utilities
```

## Getting Started

1. **Install Dependencies**:
   ```bash
   npm install
   ```
2. **Launch Dev Server**:
   ```bash
   npm run dev
   ```
   *The application will be available at `http://localhost:8080` (default port).*

## Content Management

Site content is managed via a centralized adapter in `src/lib/content.ts`. This allows for easy updates to:
- News & Articles
- Service descriptions
- Team bios
- Career openings

## Deployment

The project is configured for seamless deployment on **Vercel**. Every push to the `main` branch triggers an automatic build and deployment.

---

*&copy; 2026 B-PLAN Consulting. All rights reserved.*
