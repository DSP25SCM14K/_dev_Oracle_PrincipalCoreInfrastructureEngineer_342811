# Dev Kumar — OCI core infrastructure portfolio

A responsive static portfolio for systems engineering, high-performance networking, and cloud infrastructure. The hero uses a generated network-fabric background with subtle CSS drift; animated packet paths and interactive steady-traffic, traffic-surge, and recovery states illustrate dataplane behavior.

## Files

- `index.html` — portfolio, all 15 resume experience bullets, projects, and profile links
- `styles.css` — responsive layout, animation, and visual system
- `script.js` — rotating focus text, interactive dataplane diagram, scroll reveals, and project filters
- `network-fabric.jpg` — generated hero background image
- `.github/workflows/pages.yml` — GitHub Pages deployment workflow
- `ROLE_RESEARCH.md` — company and role research, with source links and the requisition caveat

## GitHub Pages

The site is plain HTML, CSS, and JavaScript with no build step or runtime dependencies. GitHub Actions deploys the repository root when a commit is pushed to `main`.

The Projects section lists the 23 unique projects supplied in the request. Each card links to source code; a Technical Demo link appears only for Oxide-HV, TradeSentinel, AskMyStore, and Strangers, which were supplied with demo URLs. The site omits LinkedIn and has no footer.
