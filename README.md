# KGen Website

Static site for GitHub Pages with:
- `/` (Home): KGen products & services overview
- `/products.html` (Products): four product tiles (Absence+, Enhanced HR, two placeholders)
- `/admin/hr-policy.html` (Hidden): private page for HR policy (not linked; robots noindex/nofollow)

## Deploy (GitHub Pages)
1. Create repo (or use existing) and upload these files.
2. Settings → Pages → Source: Deploy from a branch; Branch: `main` and Folder: `/ (root)`.
3. Open the Pages URL.

## Notes
- The admin page is hidden by being unlinked and marked `noindex`. It is **not password-protected**; anyone with the exact URL can view it.
- For true privacy, use a private repo or add real authentication (requires a different hosting setup).