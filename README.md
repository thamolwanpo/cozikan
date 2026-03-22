# Cozikan 🍜
A cozy kanban board for indie game development.

## Deploy to GitHub Pages (free)

1. Create a new GitHub repo (e.g. `cozikan`)
2. Upload `index.html` to the repo
3. Go to **Settings → Pages**
4. Set source to `main` branch, `/ (root)` folder
5. Click Save — your board is live at `https://yourusername.github.io/cozikan`

## Deploy to Vercel (free)

1. Go to [vercel.com](https://vercel.com) and sign in with GitHub
2. Click **Add New → Project**
3. Import your GitHub repo
4. Vercel auto-detects it as a static site — click **Deploy**
5. Done! You get a free `.vercel.app` URL

## Features
- 4 columns: Backlog / Ideas, In Progress, Needs Testing, Done / Shipped
- Drag & drop cards between columns
- Priority levels (High / Medium / Low) with color indicators
- Tags: Art, Code, Audio, Design, Writing
- Milestones / sprint grouping
- Notes / description on each card
- All data saved locally in your browser (localStorage)
- Filter board by milestone

## Keyboard shortcuts
- `Esc` — close any modal
- `Cmd/Ctrl + Enter` — save card modal
- `Enter` — create milestone (when in milestone field)
