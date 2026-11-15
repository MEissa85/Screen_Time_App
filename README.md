# Weekend Screen Time

## Put it online with GitHub Pages
1. Sign in at github.com and create a new **public** repository (e.g. `screen-time`).
2. Click **Add file → Upload files** and upload all files from this folder:
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`. Commit.
3. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**,
   branch **main**, folder **/ (root)**, then **Save**.
4. After a minute or two the address appears at the top of that page,
   e.g. `https://YOUR-NAME.github.io/screen-time/`.

## Install on Android
1. Open that address in **Chrome** on the phone.
2. Tap **Install app** at the bottom of the page, or Chrome menu (⋮) → **Install app** / **Add to Home screen**.
3. It opens full-screen from its own icon and works offline.

## Notes
- Data is stored on the device it's used on. Use one phone/tablet as the family tracker.
- The first time you tap Undo or open Admin, you'll create the admin password.
- Clearing Chrome's data for the site erases history and the password.
- To update the app later, upload the new `index.html` to the repository; the phone picks it up next time it's opened online.
