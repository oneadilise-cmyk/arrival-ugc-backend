# ⛔ DO NOT USE

These files are kept only for reference. **Do not upload, copy, or deploy them.**

The live, working site is **https://arrivalos-ugc-backend.vercel.app**, built from
**https://github.com/oneadilise-cmyk/arrivalos-ugc-backend** (note the "os"), branch `main`.
Make all future changes there.

## What's in here

| Folder | What it is | Why not to use it |
|---|---|---|
| `old-broken-version/` | The site as it was before the 25 Sept 2026 fix (commit `80c7cca` in arrivalos-ugc-backend). | The page sends requests to the homepage (error: "Unexpected end of JSON input"), the backend calls a Higgsfield address that doesn't exist (`/generate/image/nano_banana_2` → 404), and the Instagram post asks for an unsupported `4:5` size. |
| `unused-copy/` | A copy of the fix that was made in this repo by mistake. | Vercel does not build from this repo, so changes here never reach the live site. |
