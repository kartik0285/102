# Invoice Audit System

AI-powered forensic invoice auditor built with React + Vite.

## Deploy in 3 steps

### Option A — Vercel (recommended, free)

```bash
npm install
npm run build
npx vercel deploy --prod
```

When prompted, accept all defaults. Your live URL will be printed at the end.

### Option B — Netlify

```bash
npm install
npm run build
# Then drag the `dist/` folder to https://app.netlify.com/drop
```

### Option C — Run locally

```bash
npm install
npm run dev
# Open http://localhost:5173
```

## Notes

- The app calls the Anthropic API directly from the browser using your API key
- You will be prompted to enter your Anthropic API key the first time you run an audit
- Supports PDF and image invoices (JPG, PNG, WEBP)
