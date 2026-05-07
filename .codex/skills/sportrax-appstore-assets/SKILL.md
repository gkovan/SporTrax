---
name: sportrax-appstore-assets
description: Use when working with SporTrax screenshots, App Store submission assets, release image folders, marketing imagery, image dimensions, asset filenames, or visual asset organization in active-images or s3-exclude.
metadata:
  short-description: Manage SporTrax screenshots and store assets
---

# SporTrax App Store Assets

Use this skill for asset work in `/Users/gerrykovan/Documents/github/SporTrax`.

## Asset Map

- `active-images/`: current website/product images and release imagery.
- `active-images/release-1-6/`: release-specific iPhone and Apple Watch imagery.
- `s3-exclude/AppStoreScreenshots/`: App Store submission screenshots and prior screenshot sets.
- `s3-exclude/logo-icons/`: logo and icon exports.
- `s3-exclude/json-files/`: sample activity exports; treat as source data, not visual assets.

## Rules

- Do not overwrite screenshots or release assets unless the task explicitly asks for replacement.
- Preserve exact filenames and dimensions for App Store-ready assets.
- When generating new marketing art, keep it separate from real product screenshots unless asked otherwise.
- Prefer real screenshots for product and feature presentation.
- Keep generated or experimental assets clearly named and isolated from App Store submission folders.
- Before deleting or moving assets, check `git status --short` and avoid disturbing user changes.

## Workflow

1. Identify whether the request targets current web images, App Store-ready files, old screenshots, or new marketing art.
2. List affected files before modifying or generating assets.
3. Check dimensions for App Store or layout-sensitive work.
4. After changes, verify file paths used by `index.html` or submission copy still resolve.

Use image generation only when the user asks for new visuals or when a generated bitmap is clearly better than editing repo-native assets.
