# Mohammed Nazzer — Developer Portfolio

A responsive, light-theme portfolio built with Astro and deployed to GitHub Pages.

## 1. Create the GitHub repository

Create a **public** repository named exactly:

`mohammednazzer5-ui.github.io`

This special repository name publishes a user site at:

`https://mohammednazzer5-ui.github.io/`

## 2. Upload this project

Extract the ZIP, open the project folder in VS Code, then run:

```bash
npm install
npm run dev
```

Open the local URL printed by Astro (usually `http://localhost:4321`).

When ready, commit and push the project contents to the `main` branch:

```bash
git init
git add .
git commit -m "Create developer portfolio"
git branch -M main
git remote add origin https://github.com/mohammednazzer5-ui/mohammednazzer5-ui.github.io.git
git push -u origin main
```

If the repository already contains a README or other files, clone it first and copy these project files into that clone instead of running `git init`.

## 3. Enable GitHub Pages

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **GitHub Actions**.
4. Open the **Actions** tab and watch the “Deploy portfolio to GitHub Pages” workflow.
5. When the workflow succeeds, visit `https://mohammednazzer5-ui.github.io/`.

The included workflow automatically builds and deploys the site whenever you push to `main`.

## 4. Personalise before applying for jobs

Edit `src/pages/index.astro` and check every statement carefully:

- Confirm your displayed name and contact email.
- Confirm that the experience dates and education details are accurate.
- Keep only skills you can confidently discuss in an interview.
- Confirm that you have permission to display each client project.
- Add links to public GitHub repositories only when those repositories exist and you are allowed to share them.
- Replace the abstract project illustrations with real screenshots when available.

The project cards currently link to the live Immanuel USA website and the AuditForge preview. The student portal card links to Immanuel USA because it is presented as part of that platform.

## 5. Local production check

```bash
npm run build
npm run preview
```

The production output is generated in `dist/`.

## Notes

- This is a static portfolio; it does not need a server or database.
- Do not put passwords, API secrets or private client data in this repository.
- The site is configured for the special `username.github.io` repository, so no Astro `base` path is required.
