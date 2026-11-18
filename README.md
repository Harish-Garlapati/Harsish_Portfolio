# Harish Garlapati – Portfolio

Static site: plain HTML, CSS and JS. No build step.

## Files
- `index.html` – home page
- `statement-analyzer.html` – case study
- `styles.css`, `script.js` – design and scroll animations
- `resume.pdf` – the Download Resume button links here
- `assets/` – Earnmitra app screenshots
- `favicon.svg` – browser tab icon

## Run locally
Open `index.html` in a browser, or run `npx serve .` in this folder.

## Deploy on Vercel
1. Create a new GitHub repo (for example `portfolio`) and push this folder to it.
2. Go to vercel.com, sign in with GitHub, click **Add New → Project**, and import the repo.
3. Framework preset: **Other**. Leave the build command empty. Click **Deploy**.
4. Your site is live at `https://<project-name>.vercel.app`.

## Update the resume
Replace `resume.pdf` with the new file (same name), commit and push. Vercel redeploys automatically.
