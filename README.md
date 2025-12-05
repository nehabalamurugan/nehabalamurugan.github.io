# Neha Balamurugan's Personal Website

A modern portfolio website built with Next.js, TypeScript, and Tailwind CSS.

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ and npm

### Installation

```bash
npm install
```

### Development

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build

Build the static site for production:

```bash
npm run build
```

The static files will be generated in the `out` directory.

## 📦 Deployment to GitHub Pages

This site is configured for static export and can be deployed to GitHub Pages.

### Option 1: GitHub Actions (Recommended)

Create a `.github/workflows/deploy.yml` file:

```yaml
name: Deploy to GitHub Pages

on:
  push:
    branches:
      - master

jobs:
  build-and-deploy:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: actions/setup-node@v3
        with:
          node-version: '18'
      - run: npm install
      - run: npm run build
      - uses: peaceiris/actions-gh-pages@v3
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          publish_dir: ./out
```

### Option 2: Manual Deployment

1. Build the site: `npm run build`
2. Copy contents of `out` folder to the root (or use a separate branch)
3. Commit and push to GitHub

## 📝 Content

- **About**: Personal introduction and interests
- **Timeline**: Education and career timeline
- **Projects**: Showcase of hackathons, class projects, personal work, and social impact projects
- **Thoughts**: Blog posts and reflections
- **Activities**: Extracurricular activities and involvement

## 🛠️ Tech Stack

- **Next.js 16** - React framework
- **TypeScript** - Type safety
- **Tailwind CSS** - Styling
- **Radix UI** - Accessible component primitives
- **Lucide React** - Icons

## 📄 License

This project is private and personal.

