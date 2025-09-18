# Walking in Faith Ministries Website

Static website for Walking in Faith Ministries.

## Deploy to GitHub Pages (no coding required)

1. Go to https://github.com/new and create a **public** repository, e.g. `walking-in-faith-site`.
2. Download the ZIP from ChatGPT and unzip it.
3. Drag-and-drop **all files** from the unzipped folder into your GitHub repo (or use **Add files → Upload files**).
4. Click **Commit changes**.
5. Open **Settings → Pages**.
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` (or `master`) and **folder:** `/root`
   - Click **Save**.
6. Wait 1–2 minutes. Your site will be live at: `https://<your-username>.github.io/<your-repo>/`

> Optional: If you want the site at the root `https://<your-username>.github.io`, name the repo exactly `<your-username>.github.io`.

## Edit livestream + Zoom

- Update the YouTube `VIDEO_ID` in `index.html` and `livestream.html`.
- Zoom info is already set to:
  - Meeting ID: **513 621 4516**
  - Passcode: **YTR1BY**

## Custom domain (optional)

1. Buy a domain (e.g., from Namecheap or Google Domains).
2. In **Settings → Pages**, add your domain in **Custom domain** (GitHub will create a `CNAME` file).
3. In your domain’s DNS, create **CNAME** record:
   - `www` → `your-username.github.io`
4. For apex (`example.org`), add **A** records to GitHub Pages IPs (listed in GitHub docs) and redirect `@` → `www`.

## Local edits

You can edit files directly on GitHub (pencil icon) or on your computer and upload again. No build step is needed.

— Generated 2025-09-18
