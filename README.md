# nicholaslorizio site — how to publish (free, GitHub Pages)

## 1. Create the GitHub account and repository
1. Sign up free at https://github.com. Account: **nicholaslorizio**.
2. Click **New repository**. Name it exactly `nicholaslorizio.github.io` (your username + `.github.io`). Set it to **Public**. Create it.

## 2. Upload the files
1. In the new repository, click **Add file → Upload files**.
2. Drag in everything from this folder (index.html, 404.html, robots.txt, sitemap.xml and the folders about, writing, book, contact, assets). Keep the folder structure.
3. Click **Commit changes**.
4. Go to **Settings → Pages**. Under "Build and deployment," choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
5. After a few minutes the site is live at https://nicholaslorizio.github.io

**If your username is not `nicholaslorizio`:** every page and sitemap.xml contain `https://nicholaslorizio.github.io`. Replace it with `https://YOURNAME.github.io` before uploading (or ask Claude to rebuild).

## 3. Connect Google Search Console
1. Go to https://search.google.com/search-console and add a **URL prefix** property: `https://nicholaslorizio.github.io/`
2. Choose the **HTML tag** method. Copy the `content="..."` code.
3. In `index.html`, replace the commented line `<!-- <meta name="google-site-verification" content="PASTE_CODE_HERE"> -->` with the real tag (no comment markers). Upload the updated file, then click **Verify**.
4. In Search Console, open **Sitemaps** and submit `sitemap.xml`.
5. Use **URL Inspection** on `https://nicholaslorizio.github.io/about/` and click **Request indexing**.

## 4. Point every profile at the site
Add `https://nicholaslorizio.github.io/about/` as the website on LinkedIn, X, Amazon Author Central and Goodreads.

## Later
- **Headshot:** replace `assets/headshot.jpg` with a new photo of the same name to update it everywhere.
- **New Breach Brief editions:** add a line to `writing/index.html` with the edition's LinkedIn link.
- **Custom domain:** when budget allows, buy a .com, then in Settings → Pages enter it under "Custom domain." Ask Claude to update the URLs in the pages and sitemap.
