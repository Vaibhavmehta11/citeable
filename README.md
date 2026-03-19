# Citeable — Audit Pages

Hosted on GitHub Pages. Each audit is a private, tracked URL.

## URL structure
```
https://vaibhavmehta11.github.io/citeable/audit/{prospect-slug}/?prospect={id}&campaign={name}&channel={email|linkedin}&variant={v1}
```

## Current audits
- `/audit/bwd/` — Bloor West Dental

## Analytics
PostHog. Replace `REPLACE_WITH_POSTHOG_KEY` in each page after creating a free account at posthog.com.

Events tracked:
- `citeable_page_viewed`
- `citeable_session_started`
- `citeable_cta_clicked` (with cta_type + cta_location)
- `citeable_scroll_depth` (25/50/75/100%)

## Tracked outreach link format
```
https://vaibhavmehta11.github.io/citeable/audit/bwd/?prospect=bwd001&campaign=toronto-dental&channel=email&variant=v1
```
