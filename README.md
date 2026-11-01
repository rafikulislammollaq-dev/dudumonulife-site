# dudumonulife-site

Public information page for **Indian Guy: Rich Simulator** (`com.dudumonulife.app`), an Android
life-simulator game by an independent developer.

This repository exists to give the app stores a permanent, free privacy-policy URL. It is served by
GitHub Pages from the `main` branch — no hosting, no build step, no dependencies.

## Pages

| File | Purpose |
|---|---|
| `index.html` | Landing page for the app |
| `privacy-policy.html` | The policy the store listing points at |
| `store-listing.md` | Paste-ready store copy (not served to users) |
| `assets/app_icon.png` | 512×512 launcher icon, also uploaded to the store |

## Updating the policy

Edit `privacy-policy.html`, bump the "Last updated" date at the top, and push:

```sh
git add -A && git commit -m "privacy policy: <what changed>" && git push
```

The live URL does not change, so a store listing never needs re-submitting after an edit.

## Why the wording is what it is

The game has no account and no server. Player progress lives in a single JSON file inside the app's
private data directory on the device. The only network traffic after launch comes from the ad
mediation SDK (Unity LevelPlay, with Unity Ads as fill), which is why that SDK's collection is the
entirety of section 2. If a server feature is ever added, section 5 has to be rewritten before that
build ships.
