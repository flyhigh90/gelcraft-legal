# GelCraft — legal pages

Public policy pages for the **GelCraft** Android app (`com.gelcraft.app`), served via GitHub
Pages. This repository is public on purpose: Google Play requires these URLs to be reachable
by anyone, without signing in.

It contains **only** these static pages. The app source lives in a separate private
repository.

| Page | URL |
|---|---|
| Landing | `https://flyhigh90.github.io/gelcraft-legal/` |
| Privacy policy | `https://flyhigh90.github.io/gelcraft-legal/privacy.html` |
| Account deletion | `https://flyhigh90.github.io/gelcraft-legal/delete-account.html` |

## Where these URLs are referenced

Change them in all of these places if the repo is renamed or moved:

- The app: `PRIVACY_POLICY_URL` in `SettingsScreen.kt` (Settings → Privacy Policy)
- Play Console → Policy → App content → **Privacy policy**
- Play Console → Policy → App content → **Data deletion**
- The app's `docs/` folder

## Updating a policy

Edit the HTML, commit, push. GitHub Pages redeploys in about a minute. If you change anything
material, update the "Last updated" date in `privacy.html` — the policy promises users you
will.

## Contact address

Every page points at `prakash.anin@gmail.com`. That address **must actually receive mail** —
a privacy policy listing a dead contact is a compliance problem under GDPR and a support
liability on Play. Change it in all three HTML files if it is not live.
