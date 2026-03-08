# bdcloud.nl

Personal portfolio and blog of Brandon van Dijk — Cloud Architect specializing in Microsoft Modern Workplace, Endpoint Management, and Information Protection.

🌐 **Live at [bdcloud.nl](https://bdcloud.nl)**

---

## Tech Stack

- **Framework:** [Astro](https://astro.build/)
- **Styling:** Custom CSS with CSS variables (dark/light mode via `prefers-color-scheme`)
- **Content:** Astro Content Collections (Markdown)
- **Fonts:** Syne + DM Mono via Google Fonts
- **Deployment:** [Cloudflare Pages](https://pages.cloudflare.com/)
- **Analytics:** Cloudflare Web Analytics

## Project Structure

```
src/
├── content/
│   ├── config.ts         # Content collection schema
│   └── blog/             # Blog posts (.md files)
├── layouts/
│   └── Layout.astro      # Shared layout (nav, footer, global CSS)
└── pages/
    ├── index.astro        # Homepage
    ├── 404.astro          # Custom 404 page
    └── blog/
        ├── index.astro    # Blog overview
        └── [slug].astro   # Individual post
```

## Local Development

```bash
# Install dependencies
npm install

# Start dev server at localhost:4321
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Writing a Blog Post

Create a new `.md` file in `src/content/blog/`:

```markdown
---
title: "Your Post Title"
description: "A short description of your post."
date: 2026-03-08
tags: ["Intune", "Purview"]
draft: false
---

Your content here...
```

Push to `main` → Cloudflare Pages deploys automatically.

---

## Certifications

| Exam | Title | Level |
|---|---|---|
| MS-102 | Microsoft 365 Administrator Expert | Expert |
| SC-400 | Information Protection & Compliance Administrator | Associate |
| MD-102 | Endpoint Administrator Associate | Associate |
| AZ-104 | Azure Administrator Associate | Associate |
| AZ-900 | Azure Fundamentals | Fundamentals |