TIRE SPOT SIGN-OFF - SETUP

Files in this folder (upload ALL of them, keep the icons folder):
  index.html, manifest.webmanifest, sw.js, icons/

1. Put it online with GitHub Pages
   - Go to github.com and sign in.
   - Click "+" (top right) > New repository.
   - Name it: signoff. Choose Public. Click Create repository.
   - Click "uploading an existing file".
   - Drag in everything from this folder (including the icons folder). Click Commit changes.
   - Go to Settings > Pages.
   - Under "Build and deployment", Source: Deploy from a branch. Branch: main, folder: / (root). Click Save.
   - Wait 1-2 minutes. Your app is at: https://YOUR-USERNAME.github.io/signoff/

2. Install it on the Android tablet
   - Open Chrome on the tablet and go to your link.
   - Tap "Install app" at the top of the app, or Chrome menu (three dots) > Install app / Add to home screen.
   - The Sign-Off icon appears on the home screen. Open it from there.

3. First-time setup in the app
   - Tap Settings, enter 1234, set a new staff PIN, check the shop info and rates, Save.
   - Do one test job, then delete it in Records.

4. Backups (important)
   - Records live only on the tablet.
   - Once a week: Records > Back up all records. The file goes to Downloads.
     Upload it to Google Drive or email it to yourself.
   - To move to a new tablet: install the app there, then Records > Restore backup.

5. Updating later
   - Upload the new index.html to the same GitHub repository (replace the old one).
   - Open sw.js on GitHub, change VERSION (signoff-v1 -> signoff-v2), commit.
   - Close and reopen the app on the tablet twice to get the update.

Customer data is never uploaded to GitHub. Only the app itself is there.
