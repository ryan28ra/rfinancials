# R Financials — Starter Kit

Everything Claude Code needs to build the R Financials site. Quick start:

1. **Unzip** this folder somewhere on your machine.
2. **Add your brief:** drop your original written brief (the R Financials document)
   into the `brief/` folder as `rfinancials-brief.md` (or .txt / .pdf).
3. **Open the folder in VS Code:** File → Open Folder → select `rfinancials-starter`.
4. **Install the extension:** press `Cmd/Ctrl + Shift + X`, search **"Claude Code"**
   (by Anthropic), click **Install**. Sign in with your paid Claude account when
   prompted (no API key needed).
5. **Open the panel:** click the Claude Code icon in the sidebar (or the spark icon
   top-right when a file is open).
6. **Kick it off:** open `BUILD_PROMPT.md`, copy the prompt, paste it into the panel.
   Claude Code will read `CLAUDE.md` automatically and scaffold the Astro site.

## What's inside
- `CLAUDE.md`        — project context Claude Code reads every session (brand, voice, tech).
- `BUILD_PROMPT.md`  — the exact first task to paste in, plus follow-ups.
- `design/`          — the approved homepage + logo assets (light & dark versions).
- `brief/`           — put your original brief here.

## Deploying (later)
Astro builds to static files. Easiest paths:
- **Netlify:** drag-and-drop the `dist/` folder onto app.netlify.com, or connect a repo.
- **Vercel:** push to GitHub, "Import Project," Astro is auto-detected.
Then point `rfinancials.co` DNS at the host — Claude Code can walk you through it.
