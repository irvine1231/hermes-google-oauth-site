# Hermes Google OAuth Site

Static public pages for the Google OAuth consent screen used by the owner's private Hermes Google integration.

## Custom domain

The `CNAME` file contains the GitHub Pages custom hostname.

## GitHub Pages

1. Push this repository to GitHub.
2. In **Settings → Pages**, deploy from `main` and `/ (root)`.
3. Configure a custom domain owned by you.
4. Enable **Enforce HTTPS**.
5. Verify that `/`, `/privacy.html`, and `/terms.html` are publicly accessible without signing in.

## Google Cloud fields

For a custom hostname such as `oauth.example.com`:

- Homepage: `https://oauth.example.com/`
- Privacy policy: `https://oauth.example.com/privacy.html`
- Terms: `https://oauth.example.com/terms.html`
- Authorized domain: `example.com`

Verify ownership of the root domain through Google Search Console using a Google account that is an Owner or Editor of the Cloud project.
