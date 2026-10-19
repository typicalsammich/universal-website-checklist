# Universal Website SEO Checklist — Vercel-ready static site

This is a standalone website. Deploy in a NEW GitHub repository, not inside your existing Next.js project.

1. Create a new GitHub repository (e.g. universal-seo-checklist).
2. Upload `index.html` and `vercel.json` into the repository root (not inside a subfolder).
3. In Vercel, Add New > Project, import that repository.
4. Framework Preset: Other. Root Directory: `./`. Build Command: leave blank. Output Directory: leave blank (or use `.` if the UI requires a value).
5. Deploy. The website will load at the root URL.

Note: Progress saves in each browser using localStorage. It does NOT sync across browsers or devices. Export a backup JSON to transfer progress.

If you want this checklist inside an existing Next.js site, these standalone files must be integrated as a route; do not replace the Next.js project's root files.
