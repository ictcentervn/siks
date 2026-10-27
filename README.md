# SIKS ICT Expo 2026 — Public Website

A self-contained bilingual (Korean / English) static website for the SIKS ICT Expo 2026 House competition. No login, database, registration, or API keys are required.

## Pages and features
- KO / EN translation switch for the entire page
- Schedule: 12:30–15:30 on Wednesday, 4 November 2026 (tidy-up 15:30–15:50)
- House totals only (no individual student names)
- Cup Snatching, Hamster Maze Escape, and 3-on-3 Hamster Soccer rules
- House AI Video Challenge (up to five minutes per House)
- Scoring proposal and safety / consent guidelines
- Responsive mobile layout and print option

## Deploy to Vercel (no login required for visitors)
1. Create a GitHub repository and add these files at the repository root.
2. In Vercel, select Add New → Project → Import the repository.
3. Framework preset: Other. Build command: leave blank. Output directory: leave blank (repository root).
4. Deploy. Share the resulting public HTTPS address with parents and students.

## Deploy to GitHub Pages
1. Create a GitHub repository and add the files at the root.
2. Settings → Pages → Deploy from a branch.
3. Choose main / (root), then Save.
4. Share the published github.io address. No login is needed for visitors.

## Important
- House team assignments, topic allocations and judging scores are currently marked as **proposals**.
- If the event date, bracket or rules change, update the two translation dictionaries within `index.html` before distributing the public link.
- All assets are local except the optional Google Fonts stylesheet, which has system fallbacks.