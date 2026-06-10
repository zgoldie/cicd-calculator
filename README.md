# CI/CD Calculator

Compare estimated monthly costs for **Codemagic**, **GitHub Actions**, and **Bitrise**.

## For sales

**Live:** [zgoldie.github.io/cicd-calculator](https://zgoldie.github.io/cicd-calculator/)

**Burstable concurrency (Codemagic only):** [zgoldie.github.io/cicd-calculator/burstable.html](https://zgoldie.github.io/cicd-calculator/burstable.html)

**OTA updates (Codemagic CodePush vs Expo EAS Update):** [zgoldie.github.io/cicd-calculator/ota.html](https://zgoldie.github.io/cicd-calculator/ota.html)

**Simple CI/CD (mobile defaults):** [zgoldie.github.io/cicd-calculator/simple.html](https://zgoldie.github.io/cicd-calculator/simple.html)

**Simple CI/CD (mobile defaults):** [zgoldie.github.io/cicd-calculator/simple.html](https://zgoldie.github.io/cicd-calculator/simple.html)

Or open `index.html` locally in Chrome, Safari, or Edge. Adjust team size, concurrencies, macOS/Linux build volume, and CI times — results update live. Choose **M2** or **M4** for macOS pricing. Use the middle card dropdown to compare **GitHub Actions** or **Expo (EAS)**.

No install, login, or build step. Works offline locally. Keep `favicon.svg` in the same folder as the HTML.

## Files

- `index.html` — CI/CD comparison calculator (HTML, CSS, JS)
- `burstable.html` — Codemagic burstable concurrency estimate (typical p95 + burst spike)
- `ota.html` — OTA update pricing (Codemagic CodePush vs Expo EAS Update)
- `simple.html` — simplified CI/CD calculator (releases = iOS + Android, fixed 50/50 mix)
- `simple.html` — simplified CI/CD calculator (releases = iOS + Android, fixed 50/50 mix)
- `favicon.svg` — Codemagic star icon for the browser tab

## Updating pricing

Edit the constants in the `<script>` block of `index.html` (`RATES`, `CM_PLANS`, `BITRISE_PRO_TIERS`, etc.) or `burstable.html` (`CM_PLANS`).
