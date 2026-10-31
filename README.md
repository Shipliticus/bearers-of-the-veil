# Bearers of the Veil — mobile web build

This is a static web build of the current playable prototype. Serve it over **HTTPS**; do not open it as a local `file://` page or inside a restrictive attachment preview.

## Quick deploy with Netlify

1. Unzip this package.
2. Sign in to Netlify.
3. Choose **Add new site → Deploy manually**.
4. Drag the `bearers_veil_web` folder (the folder containing `index.html`) into the deploy area.
5. Open the HTTPS URL Netlify provides on Android Chrome or iPhone Safari.

## Deploy with GitHub Pages

1. Create a GitHub repository and upload the contents of this folder to its root.
2. In repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`.
3. Wait for publication, then open the HTTPS URL.

## Mobile launch

- Keep an internet connection for the first load: Three.js is loaded from a CDN, with a second CDN as fallback.
- Use a current version of Chrome on Android or Safari on iPhone.
- If WebGL is unavailable or the engine cannot be downloaded, a readable error screen and retry button appear.
- Use the browser's **Add to Home Screen** option for an app-like launch.

## Controls

Touch: joystick to move; EXAMINE, ENTER, POWER and NOTES; tap a bearer portrait to switch.
Keyboard: WASD / arrows, Space, E, F and 1–5.

This package prepares the website but does not publish it. A hosting account is needed to create the public HTTPS URL.
