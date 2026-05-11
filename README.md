# Resume Site

Static resume site for Vercel or any other static host.

## Files

- `index.html` is the landing page.
- `styles.css` is the styling.
- `resume.pdf` is the resume visitors can open or download.

## Deploy on Vercel

1. Create a new Vercel project.
2. Point it at this folder: `resume-site`
3. Framework preset: `Other`
4. Build command: leave empty
5. Output directory: leave empty

Vercel will serve the files directly.

## Vercel Analytics

1. In the Vercel dashboard, open your project and enable `Analytics`.
2. Deploy once.
3. Open `index.html` and replace `__VERCEL_ANALYTICS_PATH__` with the project-specific analytics path Vercel provides for the script route.
4. Redeploy.

The current HTML already includes the analytics bootstrap function and the script tag placeholder.

## Customizing

- Replace the heading text in `index.html`
- Replace `resume.pdf` whenever you update your resume
