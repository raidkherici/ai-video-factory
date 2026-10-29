# GitHub Pages deployment

1. Go to repository **Settings → Pages**.
2. Set **Source** to **GitHub Actions**.
3. Push to `main`; the workflow deploys the static website.
4. Check **Actions** for the workflow result and the Pages URL in **Settings → Pages**.

The website is static. No AI API key, secret, payment method, or billing integration is required. This does not make external AI-video providers free; test their current limits independently.

## Free-use safety
- Do not add billing credentials or provider API keys.
- Do not enable paid fallbacks.
- If any service requests a payment method or presents an unclear cost, stop and choose another provider.
- GitHub account quotas and policy may change; check current GitHub limits before running compute-heavy workflows.