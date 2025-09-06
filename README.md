# Mahadev Portfolio (Ready to Deploy)

This is a minimal Vite + React portfolio for **Mahadev** (Computer Science graduate, 2025).
It includes an updated summary (Experience: 0 years) and your attached resume.
The project is ready to push to GitHub and deploy on Vercel/Netlify.

## Quick deploy (Vercel)

1. Create a new GitHub repository and push the contents of this folder.
2. Go to https://vercel.com, sign in, and choose "Import Project".
3. Connect your GitHub account and select the `mahadev-portfolio` repo.
4. Set the project name to `mahadev-portfolio` (this increases the chance of getting `https://mahadev-portfolio.vercel.app`).
5. Vercel should auto-detect the framework (Vite). Build command: `npm run build`. Output directory: `dist`.
6. Click Deploy. After successful deploy you will get a live URL (e.g., https://<project-name>.vercel.app).

## Local dev

```bash
npm install
npm run dev
```

## Notes about the domain

- I cannot deploy a live site from here. To get the exact domain `https://mahadev-portfolio.vercel.app`, create the Vercel project with the name `mahadev-portfolio` and deploy. If that exact hostname is available, Vercel will assign it; otherwise Vercel will provide a similar URL.
- If you prefer, you can assign a custom domain and configure it in Vercel settings.
