# social-assets

Public image assets for **scheduled social-media posts**.

These files exist to be fetched **once** by Zoho Social's bulk scheduler at publish
time — it needs a public, direct image URL (ending in `.jpg`/`.jpeg`). Once a post
publishes, the social platform re-hosts its own copy, so these URLs are just pickup
points.

**Marketing graphics only — nothing private or sensitive.** This repo is public.

**Layout:** `<brand>/<yyyy-mm>/<slug>.jpg`
e.g. `techromatic/2026-08/backup-is-a-hope.jpg`

Raw URL pattern (what goes in the bulk-scheduler `Media` column):
`https://raw.githubusercontent.com/PaulSmithCC/social-assets/main/<path>`
