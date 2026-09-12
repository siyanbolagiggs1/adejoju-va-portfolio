# Adejoju VA Agency — Capstone Portfolio

A one-page portfolio site built for the TS Academy Virtual Assistance capstone
project. It covers the three required tasks:

1. **Agency Launch (Trello)** — your "Adejoju VA Agency Launch" board, embedded
   as a screenshot with a short write-up.
2. **Brand Kit** — a placeholder section styled with a suggested palette/fonts,
   ready to swap for your real Canva Brand Kit.
3. **Skills Self-Assessment** — placeholder cards for strengths, gaps, and your
   improvement plan.

Plain HTML/CSS/JS — no build step, no framework, no dependencies.

## ✏️ Before you submit — personalize these

Search the page for the ✏️ notes (also easy to find with Ctrl+F "editable-note"
in `index.html`), and fill in:

- [ ] Your real name/last name in the hero, nav, and page `<title>` (currently just "Adejoju")
- [ ] The "About Me" paragraph
- [ ] Brand Kit section: your actual Canva design (image), real colours/fonts,
      and what the brand represents — replace the dashed placeholder box in
      `index.html` (`.brand-placeholder`) with an `<img>` of your brand kit
- [ ] Skills Self-Assessment: your real strengths, skill gaps, and improvement
      plan from the completed assessment
- [ ] Contact section: phone / LinkedIn / WhatsApp if you want them listed
      (email is pre-filled with siyanbolagiggs@gmail.com)

## Run it locally

Just open `index.html` in a browser, or serve it:

```bash
npx serve .
```

## Deploy to Render (free Static Site)

1. Push this folder to a GitHub (or GitLab) repository.
2. In the [Render dashboard](https://dashboard.render.com), click **New +** →
   **Static Site**.
3. Connect the repository.
4. Settings:
   - **Build Command:** leave blank
   - **Publish Directory:** `.` (repo root)
5. Click **Create Static Site**. Render will give you a live URL like
   `https://adejoju-va-portfolio.onrender.com`.

A `render.yaml` is included if you prefer Render's [Blueprints](https://render.com/docs/blueprint-spec)
(New + → Blueprint, point it at this repo) instead of the manual steps above.

## Deploy with git + Render CLI (optional)

```bash
git init
git add .
git commit -m "Initial VA capstone portfolio"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```

Then connect that repo on Render as described above.
