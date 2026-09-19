# Flipbook Library for GitHub Pages

Static prototype inspired by modern PDF flipbook libraries.

## Deploy
1. Create a GitHub repository.
2. Upload `index.html`, `style.css`, `app.js`.
3. Settings → Pages → Deploy from branch → `main` / root.

## Important security note
This prototype stores PDFs and passwords in `localStorage` and is **not secure for confidential documents**. Anyone with browser/devtools access can inspect the data. For real protection, use a backend/storage service (e.g. Supabase/Firebase) with server-side authorization, signed URLs, and hashed passwords. GitHub Pages alone cannot securely protect private PDFs.
