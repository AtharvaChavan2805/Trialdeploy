# Trialdeploy — Vite + React (Hello World)

This repository contains a minimal Vite + React app ready to deploy to Vercel.

Quick commands (PowerShell):

```powershell
# install
cd d:\trial\Trialdeploy
npm install

# dev server
npm run dev

# build
npm run build

# preview build locally
npm run preview
```

To deploy on Vercel:

1. Push this repo to GitHub (see commands below).
2. Import the GitHub repo into Vercel (vercel.com) and use the default build settings.
   - Build command: `npm run build`
   - Output directory: `dist`

Example Git commands to push (if your local repo is in `d:\trial\Trialdeploy`):

```powershell
cd d:\trial\Trialdeploy
git add .
git commit -m "chore: add Vite React scaffold for Vercel"
git push origin main
```

If you want TypeScript instead, or prefer yarn/pnpm, tell me and I will adapt the scaffold.
