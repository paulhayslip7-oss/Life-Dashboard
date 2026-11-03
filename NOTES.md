# Status & handoff notes

Read this first when picking the project up in a new session, on any device. Update it at the end of each session.

_Last updated: 2026-11-03_

## Where things stand
- `dashboard.html`: a single-file dashboard ("Paul's Dashboard"): Today's Focus, Gratitude, Habits, Top Tasks, Quote of the Day, plus Spotify (PKCE OAuth + playback controls).
- `Organized Life.zip`: a high-fidelity **design handoff** for a bigger rebuild, "Organized Life — Editorial Operator" (broadsheet × Bloomberg-terminal look). 8 screens: Morning, Tasks, Habits, Goals, Athletic, Finance, Build (ventures kanban), Wires (integrations). Includes React prototypes, a `dataLayer.js` and a Supabase `migration.sql`. Not implemented yet.
- PR #1 (Spotify + "Netlify auto-deploy") was closed: its Spotify work is already on `main`, and it contained no Netlify setup.

## Open questions for Paul
- [ ] Build the "Organized Life" design as a real app (e.g. React + Vite + Supabase, like SimpleCRM), or keep evolving `dashboard.html`?
- [ ] Where should it be hosted? (Auto-deploy was never actually set up.)

## Next up
1. Decide the questions above.
2. If rebuilding: scaffold the app, implement the Morning screen first, then Tasks / Habits, wiring data through Supabase so phone and computer share it.
