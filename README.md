# Prompt to JSON Generator

A production-ready, client-only React app that turns structured scene settings into JSON.
- Add multiple prompts
- Configure settings (lighting, mood, palette, etc.)
- Add negative prompts
- Copy JSON to clipboard
- Download as `.txt`
- Clear & restart

## Local Dev
```bash
npm i
npm run dev
```

## Build
```bash
npm run build
npm run preview
```

## Deploy (Vercel, Netlify, Cloudflare)
This is a static site. Import the repo and set:
- **Build Command**: `npm run build`
- **Output Directory**: `dist`
