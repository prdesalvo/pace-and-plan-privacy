# Pace and Plan product page

Product/share URL: https://prdesalvo.github.io/pace-and-plan-privacy/pace-and-plan/

Buildless HTML and CSS, using the existing privacy repository’s GitHub Pages hosting.
The root policy, support page and Jekyll configuration remain separate from this directory.

The four screenshots were prepared for App Store Connect on November 18, 2026
from the app at `76cb358` with the isolated demo store. Their source is documented
in Training Insights’ `AppStore/first-release.md`. They contain sample data.
The icon is an iOS Default rendition exported from the current graphite
`TrainingInsights/AppIcon.icon` with Icon Composer’s official `ictool`.

The single unmodified official Apple badge is shown at 56 pixels high with
14 pixels of surrounding space. Source:
https://toolbox.marketingtools.apple.com/api/assets/featured-content/apps/badges/badge-2/en-us.svg

The page presents the app with its normal download link, as Paul requested,
without a coming-soon state. Store URL: https://apps.apple.com/app/id6819088583.

Open Graph and Twitter metadata are in the initial HTML. Render
`share-source.html` at 1200 × 630 and export it as `assets/share-v1.jpg`.
Use a new filename when replacing the artwork because link previews are cached.

Use the product URL as the Marketing URL on the next editable iOS and Mac
version localizations. Privacy and support keep their existing URLs.

No analytics, external fonts, JavaScript dependencies or build step.
