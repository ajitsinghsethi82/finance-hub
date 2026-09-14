# Finance Hub

Public homepage and privacy policy for the private Finance Hub bookkeeping application.

This repository contains only static information pages. Do not add financial records, credentials, OAuth tokens, or collector runtime state.

## Enable hosting
In Settings > Pages, select **Deploy from a branch**, then **main** and **/(root)**, and Save. No build tools, workflow secrets, or custom domain are required.

Expected addresses after deployment:
- Homepage: https://ajitsinghsethi82.github.io/finance-hub/
- Privacy: https://ajitsinghsethi82.github.io/finance-hub/privacy.html

Open both pages signed out and verify them before using the URLs for OAuth production setup. Site deployment does not by itself establish Google OAuth verification.

## Checkpoint — September 14, 2026
- Added index.html, privacy.html, styles.css and .nojekyll.
- Checked local navigation targets, static-only content, and Finance Hub branding.
- Google Cloud app name should be Finance Hub; replace the earlier proposed homepage/privacy paths with the addresses above.
- Pages activation and live URL verification are still pending.
- The support email is intentionally public and matches the OAuth support contact.

## Editing
Edit the HTML and shared stylesheet directly. Keep the privacy policy aligned with the actual collector before deploying data-practice changes.
