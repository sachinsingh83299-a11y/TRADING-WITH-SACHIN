# Android shell

This is a lightweight Android WebView shell around the production frontend. The market-data backend stays server-side; the APK does not contain broker credentials or API secrets.

For production, change the frontend's Gateway URL to your HTTPS backend or provide a deployment-specific configuration layer. Do not use `usesCleartextTraffic=true` in production.

Build through the repository's GitHub Actions workflow: **Build NIFTY Option AI APK**.
