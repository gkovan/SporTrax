---
name: sportrax-static-web
description: Use when editing or reviewing the SporTrax static website in this repo, especially index.html, privacy-policy.html, HTML/CSS layout, responsive behavior, image references, theme behavior, accessibility, or local browser verification.
metadata:
  short-description: Build and verify the SporTrax static site
---

# SporTrax Static Web

Use this skill for web work in `/Users/gerrykovan/Documents/github/SporTrax`.

## Repo Context

- This repo is currently a static site and marketing/App Store asset repository for SporTrax.
- Primary web files: `index.html`, `privacy-policy.html`.
- Current product imagery lives in `active-images/`.
- App Store and historical assets live mostly under `s3-exclude/`.
- Do not add React, Vite, Tailwind, package managers, or build tooling unless the user explicitly asks.

## Implementation Guidance

- Prefer direct HTML/CSS edits that preserve the static-site workflow.
- Keep the Apple Watch/iPhone product visible and inspectable in the first viewport when editing the home page.
- Use real app screenshots from `active-images/` before decorative or generated imagery.
- Preserve a polished Apple/SF-style feel: restrained motion, clear hierarchy, comfortable spacing, and strong mobile behavior.
- Avoid large decorative cards around whole page sections. Use cards only for repeated items, modals, or genuinely framed content.
- Keep copy concise and product-specific. Do not use visible instructions explaining how the UI works.
- Verify every changed image path exists.

## Verification

After meaningful HTML/CSS changes:

1. Check `git diff -- index.html privacy-policy.html` for unintended churn.
2. Open or test the changed page in a browser.
3. Inspect at desktop and mobile widths.
4. Look for broken images, overflow, overlapping text, weak contrast, and dark/light theme regressions.

If a local server is useful, prefer a simple static server from the repo root.
