# Pearl privacy website

Standalone public website for Pearl's privacy policy and support page, separate from the private Pearl iOS repository.

Public URL: https://matthew-hughes3488.github.io/pearl-privacy/

Plain HTML and CSS, with no build step, JavaScript, analytics or external assets. GitHub Pages publishes the root of `main` automatically after pushes.

- `index.html`: privacy policy
- `support.html`: support page
- `styles.css`: shared styles, using Pearl's Bloom colours

Owner/contact supplied by the operator: Matthew Hughes, 12hughesm@gmail.com.

## Content evidence

Checked against the Pearl app's code and docs on 2 October 2026: `backend.md`, `PearlData.swift`, `PearlFile.swift` and the app's entitlements for on-device storage, and, on branch `feature/backend`, the PostHog configuration and events (`PostHogAnalytics.swift`, `AnalyticsService.swift`, `AnalyticsSelection.swift`, `DayCountReporting.swift`), the lines request (`RemoteLines.swift`, `RemoteLinesClient.swift`) and the Settings screen. RevenueCat isn't wired in the app yet, so its section follows the plan in `backend.md`. Supabase's region and the 16+ age were supplied by the operator.

## Editing

Edit the HTML and `styles.css`, then commit and push to `main`. Check factual claims against the app before changing the policy, and keep the same URL.
