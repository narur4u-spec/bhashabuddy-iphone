# BhashaBuddy iPhone Home Screen App

This package prepares the existing BhashaBuddy HTML app as a Progressive Web App (PWA).

## Publish with GitHub Pages
1. Create a new GitHub repository (for example, `bhashabuddy-iphone`).
2. Upload every file/folder in this ZIP to the repository root. Ensure `index.html` is at the root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select branch `main` and folder `/ (root)`, then Save.
5. Wait for GitHub Pages to publish and open the URL it provides. It will look like:
   `https://YOUR-USERNAME.github.io/bhashabuddy-iphone/`

## Install on iPhone
1. Open that HTTPS URL in **Safari** on the iPhone.
2. Tap **Share** → **Add to Home Screen**.
3. If shown, enable **Open as Web App**, then tap **Add**.

## Notes
- This is a Home Screen web app (PWA), not a signed native iOS `.ipa`.
- The app needs to be opened online once to load and install. The service worker then caches the app shell for offline reopening.
- Browser/device capabilities such as speech recognition and speech synthesis can vary on iPhone. Test microphone and audio features on the actual device.
- GitHub Pages sites are publicly accessible. Do not upload private data or secrets.
