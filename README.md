# Personal Vault Legal Pages

This repository contains static legal-information pages for the Personal Vault Android app.

## Files
- `index.html` — landing page
- `privacy-policy.html` — privacy policy
- `terms.html` — terms and conditions

## Before publishing

1. Replace `[REPLACE WITH YOUR NAME OR BUSINESS NAME]` in both legal pages.
2. Replace `[REPLACE WITH A CONTACT EMAIL ADDRESS]` with an email address you monitor.
3. Review the privacy policy against the exact release build. In particular, disclose any analytics, crash-reporting, advertising, attribution, or other third-party SDKs and their data collection.
4. Revisit the security disclosure if application-level encryption is implemented. Do not remove or change it until the released build actually provides the stated protection.
5. Consider having the policy and terms reviewed for the jurisdictions where you distribute the app.

## Publish with GitHub Pages

1. Create a **public** GitHub repository (for example, `personal-vault-legal`).
2. Upload the contents of this ZIP to the repository's root (the files should not be nested inside another folder).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. After GitHub Pages publishes the site, use:
   - `https://YOUR-GITHUB-USERNAME.github.io/personal-vault-legal/`
   - `https://YOUR-GITHUB-USERNAME.github.io/personal-vault-legal/privacy-policy.html`
   - `https://YOUR-GITHUB-USERNAME.github.io/personal-vault-legal/terms.html`

Use the Privacy Policy URL in the Google Play Console. You can also link to these pages from the app's Settings → Legal screen.

## Important

These are editable starter documents, not legal advice. Confirm every statement against the actual app and its release configuration before publishing. The privacy policy currently reflects the project details provided for this draft: local-only vault functionality, no developer-operated backend, and no application-level encryption in the current implementation.
