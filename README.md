# fowcus-legal

Public hosting for the FOWCUS iOS app's Privacy Policy.

- `privacy.html` — Privacy Policy
- `index.html` — Landing page
- `style.css` — Shared styles

Served via GitHub Pages. URL is submitted in App Store Connect.

Keep `privacy.html` in sync with `app/legal/privacy.tsx` in the main FOWCUS
repo. Apple requires the in-app text and the hosted text to match verbatim.

Terms of Service is shown only in-app (`app/legal/terms.tsx`) since the
App Store listing uses Apple's standard EULA.
