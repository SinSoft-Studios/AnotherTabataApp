# Another Tabata App

Static product and privacy pages for Another Tabata App by SinSoft Studios.
Uses the same buildless HTML layout and `docs/` structure as the Kitty Catty Go site.

## GitHub Pages

After these files are committed and pushed to `main`, open this repository's
**Settings > Pages** and choose **Deploy from a branch**, branch **main**, folder **/docs**.
No package installation, build command, custom domain, or Actions workflow is required.

With the default GitHub Pages domain, the expected addresses are:

- Home: https://sinsoft-studios.github.io/AnotherTabataApp/
- Privacy policy: https://sinsoft-studios.github.io/AnotherTabataApp/privacypolicy/anothertabataapp.html

Use the privacy-policy address in the store listing. Links within the site are relative
so they also work under a repository path or a custom domain.

## Files

- `docs/index.html`: app introduction, privacy link, support email, and resource placeholders.
- `docs/privacypolicy/anothertabataapp.html`: app-specific privacy policy.
- `docs/.nojekyll`: serves the HTML directly without Jekyll processing.

## Maintenance

The privacy policy was expanded on October 15, 2026 for planned Google AdMob banners,
including personalized ads only where permitted and consented to, for a general adult audience.
It distinguishes ad-supported versions from the current placeholder-only app. It covers SDK data,
ad purposes/providers, consent and withdrawal, regional choices, retention/deletion, security,
transfers, and rights, with links to official Google resources.

Implementation handoff lives in the actual app source repository at
`../TabataApp/DOCS/ADS_AND_PRIVACY.md` (currently `C:\DEV\TabataApp\DOCS\ADS_AND_PRIVACY.md`).
That guide records research sources, product decisions, implementation entry points, and release checks.
The SDK, consent flow, Privacy choices action, regional opt-outs, and Play declarations still need
implementation/configuration before production ads. Keep the policy aligned with the shipped SDK
and actual account settings; adding mediation or other collection requires another review.
Store availability is not claimed on the homepage until a listing is confirmed.

Keep each product's policy separate; do not copy disclosures about another app's SDKs.
Support currently uses `sinsoftstudios@gmail.com`, matching the Kitty Catty Go site.
