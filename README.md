# CI/CD Calculator

Compare estimated monthly costs for **Codemagic**, **GitHub Actions**, and **Bitrise**.

## For sales

1. Open `pricing-calculator.html` in Chrome, Safari, or Edge (double-click the file, or host the folder on any static server).
2. Adjust team size, concurrencies, macOS/Linux build volume, and CI times with the sliders.
3. Choose **M2** or **M4** for macOS pricing — results update live.

No install, login, or build step. Works offline if you open the HTML file locally. Keep `favicon.svg` in the same folder as the HTML.

## Files

- `pricing-calculator.html` — single-file app (HTML, CSS, JS)
- `favicon.svg` — Codemagic star icon for the browser tab

## Updating pricing

Edit the constants in the `<script>` block of `pricing-calculator.html` (`RATES`, `CM_PLANS`, `BITRISE_PRO_TIERS`, etc.).
