# Pre-Discovery Intake Form

Static site hosting the client-facing pre-discovery requirements intake form.

## Local Development

Just open `index.html` in a browser — no build step required.

## Deploying to Render

1. Push this repo to GitHub.
2. Log in to [Render](https://render.com) and click **New → Static Site**.
3. Connect your GitHub account and select this repository.
4. Use these settings:
   - **Name:** your-site-name (e.g. `intake-form`)
   - **Branch:** `main`
   - **Root Directory:** *(leave blank)*
   - **Build Command:** *(leave blank)*
   - **Publish Directory:** `.`
5. Click **Create Static Site**.

Render will deploy the site and give you a URL (e.g. `https://intake-form.onrender.com`).

Any push to `main` will automatically redeploy.
