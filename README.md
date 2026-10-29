# AI Video Factory

A free-first browser workspace for planning AI-assisted videos.

## Current features
- Create a video brief and master prompt in the browser.
- Choose format (9:16, 16:9, 1:1), duration, visual style, audio plan, and output language.
- Generate a scene breakdown, copy it, or download it as TXT.
- No server upload, API key, or payment integration is used by this starter app.

## Important limitation
This is a planning tool, **not an AI video generator**. It does not call an external model or claim that any provider is free. Real video generation and export must be tested separately under the provider's current terms. Do not enable paid fallback or add a payment method.

## Publish with GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, select **GitHub Actions** as the source.
3. The workflow in `.github/workflows/deploy-pages.yml` deploys the static site on pushes to `main`.
4. Open the Pages URL shown by GitHub after the workflow succeeds.

## Local preview
Open `index.html` in a modern browser. The app works client-side.

## Privacy and cost
The page keeps the entered brief in the browser and does not send it to a server. GitHub Pages hosting is separate from any external AI generation provider. This repository does not configure paid AI APIs or automatic paid fallbacks.