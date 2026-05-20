# Habion — Legal & Support pages

Markdown sources for the public-facing legal documents required by the
Apple App Store and Google Play Store.

| File | Language | Submit as |
| --- | --- | --- |
| `privacy.md` | English | Privacy Policy URL (default locale) |
| `privacy.tr.md` | Türkçe | Privacy Policy URL (tr locale) |
| `support.md` | English | Support URL (default locale) |
| `support.tr.md` | Türkçe | Support URL (tr locale) |

## Before submitting to a store

1. **Replace placeholders**
   - `Ininia` → your real legal name or company
   - `support@habion.app` → a real, monitored email address
2. **Update the "Effective date" / "Yürürlük tarihi"** if you make material changes later.

## Hosting options

### A. GitHub Pages (recommended, free)

1. Push this repository (or a public mirror) to GitHub.
2. In the repo: **Settings → Pages → Source = "Deploy from a branch"**, branch `main`, folder `/docs`.
3. After ~1 minute, the URLs become:
   - `https://<your-user>.github.io/<repo>/legal/privacy`
   - `https://<your-user>.github.io/<repo>/legal/privacy.tr`
   - `https://<your-user>.github.io/<repo>/legal/support`
   - `https://<your-user>.github.io/<repo>/legal/support.tr`
4. Optional: add a `CNAME` file pointing to a custom domain like `habion.app`.

### B. Notion / Bear / any markdown host

These markdown files are plain CommonMark — paste into a Notion public page,
Bear web export, or similar service. The store reviewers just need a public
HTTPS URL that renders the content; the source format does not matter.

### C. Custom site

If you ship a marketing site (`habion.app`), serve these pages as
`/privacy` and `/support` (with `/privacy/tr` etc. for localized variants).

## Submitting to the stores

### App Store Connect
- **App Privacy → Privacy Policy URL** = privacy URL (per default locale).
- **App Information → Support URL** = support URL.
- Add localized URLs for the `tr` (and any other) locale via
  **App Store → App Information → Localizations**.

### Google Play Console
- **Policy → App content → Privacy Policy** = privacy URL.
- **Store presence → Main store listing → Contact details** = support
  email and URL.
- Add per-language listings under **Store presence → Custom store
  listings / Localizations**.
