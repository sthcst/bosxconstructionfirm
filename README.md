# Caisson Building Co. — Portfolio Site

A single-page static site (HTML/CSS/JS, no build step, no dependencies besides Google Fonts).

## Deploying with GitHub Pages

1. Create a new repository on GitHub (e.g. `caisson-site`).
2. Upload `index.html` to the root of the repo (drag-and-drop works fine, or `git add` + `git push`).
3. Go to the repo's **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Set **Branch** to `main` (or `master`) and folder to `/ (root)`, then **Save**.
6. Wait 1–2 minutes. Your site will be live at:
   `https://<your-github-username>.github.io/<repo-name>/`

## Custom domain (optional)

In the same **Pages** settings panel, enter your domain under **Custom domain**, then add
a `CNAME` record at your domain registrar pointing to `<your-github-username>.github.io`.
GitHub will show a pending/verified status once DNS propagates.

## Notes

- The contact form is front-end only right now — it shows a confirmation message but
  doesn't send anywhere. Wire it up to Formspree, Netlify Forms, or a backend of your
  choice before relying on it for real leads.
- Company name, project details, testimonials, and contact info are placeholders —
  search the file for `Caisson` and the sample project names to swap in real content.
