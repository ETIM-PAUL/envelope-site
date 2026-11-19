# Envelope site

The marketing site for [Envelope](https://github.com/ETIM-PAUL/Envelope), a private payments wallet for Android on Solana, and the home of its APK releases.

- `index.html`: the landing page (self-contained; screenshots in `landing/`).
- `verify.html`: the statement verify page. It is generated from the app repo (`npm run cbridge:build` writes `docs/verify.html`); copy the result here.
- Releases: each release carries `envelope.apk` (all devices) and `envelope-arm64-v8a.apk` (smaller, for any recent phone). The page links to `releases/latest/download/envelope.apk`, so keep that exact file name.

The site is served by GitHub Pages from the `main` branch root.
