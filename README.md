# Wedding page: how to put it online with GitHub Pages (free)

1. Create a free account at github.com and click New repository. Name it, for example, `wedding`. Set it to Public.
2. Click "uploading an existing file" and upload `index.html` and your prenup photo (for example `prenup.jpg`). Click Commit changes.
3. Go to Settings > Pages. Under "Build and deployment", choose "Deploy from a branch", pick the `main` branch and the `/ (root)` folder, then Save.
4. After a minute, your page is live at `https://YOUR-USERNAME.github.io/wedding/`. Share this link with your guests.

## Changing things later (admin panel)
1. Open `https://YOUR-USERNAME.github.io/wedding/#admin` (note the `#admin` at the end).
2. Click "Admin panel" and enter your password.
3. Change guests, seats, rules, dress code, etc., then click "Save & download".
4. A new `index.html` downloads. In GitHub, open your repo, click Add file > Upload files, drop in the new `index.html` (it replaces the old one), and Commit. The live page updates within a minute.

## Notes
- Background photo: upload the photo to the same repo, then type its file name in the admin panel (keep it under about 1 MB so the page loads fast).
- Guest photo uploads: paste a Google Photos / Google Drive shared-album link in the admin panel.
- The password check happens inside the page, so it only keeps casual visitors out. Do not store sensitive information in the page.
- The guest list is stored inside the page, so a technical visitor could see all names and seats.
