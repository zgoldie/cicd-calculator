# CI/CD Calculator

Compare estimated monthly costs for **Codemagic**, **GitHub Actions**, and **Bitrise**.

## For sales

**Live:** [zgoldie.github.io/cicd-calculator](https://zgoldie.github.io/cicd-calculator/)

Or open `index.html` locally in Chrome, Safari, or Edge. Adjust team size, concurrencies, macOS/Linux build volume, and CI times — results update live. Choose **M2** or **M4** for macOS pricing.

No install, login, or build step. Works offline locally. Keep `favicon.svg` in the same folder as the HTML.

## Files

- `index.html` — single-file app (HTML, CSS, JS)
- `favicon.svg` — Codemagic star icon for the browser tab

## Updating pricing

Edit the constants in the `<script>` block of `index.html` (`RATES`, `CM_PLANS`, `BITRISE_PRO_TIERS`, etc.).
