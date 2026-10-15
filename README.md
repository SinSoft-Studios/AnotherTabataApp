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

The initial app description and privacy text reflect the local TabataApp source and
its documentation reviewed on October 15, 2026: local workout/settings/recovery storage,
optional notifications and speech, and an ad placeholder without live advertising.
Before publishing a new app version, compare the policy against that release, especially
if adding advertising, analytics, crash reporting, accounts, or network services. Update
the policy date when its content changes. Store availability is intentionally not claimed
on the homepage until a listing is confirmed.

Keep each product's policy separate; do not copy disclosures about another app's SDKs.
Support currently uses `sinsoftstudios@gmail.com`, matching the Kitty Catty Go site.
