# mockingbird-test — Status
_Auto-updated by Status Brain on every push. Last change: Added Status Brain workflow and script to auto-generate project status._

**Status:** Prototype  
**What it is:** A Next.js 15 starter app with a basic API route and automated status reporting.  
**Stack:** Next.js 15, React 19, TypeScript, Tailwind CSS.

## What works right now
- Next.js dev server runs locally (`npm run dev`)
- Basic homepage at `/` (default Create Next App template)
- API route at `/api/hello` that returns JSON
- Linting with ESLint
- Tailwind CSS configured
- Status Brain workflow: generates STATUS.md on every push

## Recent changes (newest first)
- 2026-07-20 — Added Status Brain workflow to `.github/workflows/` to auto-generate project status
- 2026-07-20 — Added Status Brain script (`status-brain.mjs`) to read code and write status reports
- 2025-06-13 — Updated Next.js to version 15.3.1 and added `/api/hello` route
- 2025-06-13 — Initial project setup with Create Next App

## Reusable parts (for other projects)
- **Status Brain** — Automated status reporting that scans repo state and generates plain-English project summaries — `status-brain.mjs` + `.github/workflows/status-brain.yml`

## Not done / next
- No real feature beyond the Next.js scaffold
- No business logic or domain code
- No tests
- Homepage still shows default template
- API `/hello` route is a placeholder with no real purpose
