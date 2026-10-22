GitHub Pages deployment for Aurelia Admin Portal

1. Upload admin.html to the same GitHub repository as your website's index.html.
2. Keep the filename admin.html so the portal opens at:
   https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/admin.html
3. In GitHub, open Settings > Pages, select Deploy from a branch, choose the branch (usually main) and folder (usually /root), then Save.
4. Keep your existing website files in their current paths. The admin page's Website link points to index.html.

Important:
- This package leaves the existing Firebase/backend code and configuration unchanged.
- GitHub Pages hosts static files only; it does not configure Firebase permissions or security rules.
- Ensure your existing Firebase Firestore rules are configured appropriately for the live website/admin portal.
