# ZS | Tamim Hasan — Render Static Site

This is a static HTML website. It does not require a backend, Node.js, or a build step.

## Deploy with GitHub + Render

1. Create a new **public or private GitHub repository** (for example, `zs-tamim-hasan`).
2. Upload the three files in this folder to the repository's **root**:
   - `index.html`
   - `render.yaml`
   - `README.md`
3. In Render, choose **New + → Blueprint** and connect the GitHub repository.
4. Render detects `render.yaml`. Review the service and click **Apply**.
5. Wait for the deploy to finish, then open the `onrender.com` URL shown by Render.

## Alternative: create a Static Site manually

1. In Render choose **New + → Static Site** and connect this GitHub repository.
2. Set **Branch** to `main` (or the branch you uploaded to).
3. Leave **Build Command** empty.
4. Set **Publish Directory** to `.` (a single dot).
5. Click **Create Static Site**.

The site uses external Google Fonts and its social/contact links open third-party services. Those require an internet connection. The large profile/preview image is embedded in the HTML, so no separate image file is needed.
