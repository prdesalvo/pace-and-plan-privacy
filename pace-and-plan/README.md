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

## Deeper iPhone Trends screenshots, November 18, 2026

Replaced the website's iPad image with three native iPhone captures: Recovery,
Training load, and Strength progression / Muscle balance. Each image opens full size.
Captured on iPhone 18 Pro Max, iOS 27.0, from the installed demo app 1.1.1 (62),
launched with `--screenshot-store --demo-data`. All three are unaltered 1320 × 2868
JPEG screenshots with synthetic sample data. Binary SHA-256:
`fc4dbcd448fa2431d1ff205ab0e4b7c3a8356385ada4d69a519942eca30165a7`.
These captures are also added to the editable 1.1.2 iPhone screenshot set.
The iPad screenshot set in App Store Connect remains separate.

## Core running and metrics chat, November 18, 2026

Lead with weekly mileage and individual runs, the easy/hard heart-rate split,
and weekly speed work. Metrics chat has its own main section. Recovery and
strength screenshots follow these core views. The hero and share artwork now
show weekly mileage. New unaltered iPhone 18 Pro Max captures use the same
isolated screenshot store and sample data described above.

Intended iPhone listing order: Calendar, Weekly mileage, Heart-rate zones,
Speed work, Metrics chat, Trends overview, Strength, Recovery, Training load,
Strength trends. iOS 1.1.2 was already Waiting for Review when these core
assets were prepared; screenshot changes require returning it to an editable
state, then resubmitting. Do not withdraw a submission without Paul's approval.

The chat capture shows the actual question-entry screen. Apple Intelligence was
unavailable in the simulator, so no generated conversation is pictured.
