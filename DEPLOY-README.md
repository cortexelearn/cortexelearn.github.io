# CortexEdge — Landing Page

The root landing page for cortexelearn.github.io. Links out to the seven
standalone track sites.

## IMPORTANT — this goes in the SPECIAL repo
This must be deployed to the repo named exactly:  cortexelearn.github.io
That repo serves at the ROOT (https://cortexelearn.github.io/) with no subpath.

## Files
- index.html        the landing page
- manifest.json     PWA manifest (optional install)
- assets/logo.png   extracted CortexEdge logomark
- assets/hero-bg.jpg aerospace hero background

## Deploy
1. Use (or create) the repo named exactly: cortexelearn.github.io
2. Upload the CONTENTS of this folder (index.html, manifest.json, assets/) to the repo ROOT.
3. Settings -> Pages -> Deploy from branch: main, folder / (root).
4. Open https://cortexelearn.github.io/

## Track links (must match deployed repos)
- /ai-mastery/
- /copilot/
- /mba/
- /additive-manufacturing/
- /electric-motors/
- /embedded-platforms/
- /agentic-ai/

If you rename any track repo, update the matching href in index.html.

## Note on stats
Hero shows 7 tracks / 98 lessons / 371 exam questions (53 per track x 7).
Update these numbers in index.html if track content changes.
