# Codemagic Experiments

Sales and demo tools for mobile CI/CD — pricing calculators, yaml builder, and more.

**Live:** [zgoldie.github.io/codemagic-experiments](https://zgoldie.github.io/codemagic-experiments/)

## Tools

**CI/CD pricing calculator:** [index.html](https://zgoldie.github.io/codemagic-experiments/) — compare estimated monthly costs for **Codemagic**, **GitHub Actions**, and **Bitrise**.

**Burstable concurrency (Codemagic only):** [burstable.html](https://zgoldie.github.io/codemagic-experiments/burstable.html)

**OTA updates (Codemagic CodePush vs Expo EAS Update):** [ota.html](https://zgoldie.github.io/codemagic-experiments/ota.html)

**codemagic.yaml builder (iOS & Android):** [yaml-builder.html](https://zgoldie.github.io/codemagic-experiments/yaml-builder.html)

**Simple CI/CD (mobile defaults):** [simple.html](https://zgoldie.github.io/codemagic-experiments/simple.html)

Open any `.html` file locally in Chrome, Safari, or Edge. No install, login, or build step. Works offline locally. Keep `favicon.svg` in the same folder as the HTML.

## Files

- `index.html` — CI/CD comparison calculator (HTML, CSS, JS)
- `burstable.html` — Codemagic burstable concurrency estimate (typical p95 + burst spike)
- `ota.html` — OTA update pricing (Codemagic CodePush vs Expo EAS Update)
- `yaml-builder.html` — staged `codemagic.yaml` wizard (unsigned → signing → tests → distribution)
- `simple.html` — simplified CI/CD calculator (releases = iOS + Android, fixed 50/50 mix)
- `favicon.svg` — Codemagic star icon for the browser tab

## Updating pricing

Edit the constants in the `<script>` block of `index.html` (`RATES`, `CM_PLANS`, `BITRISE_PRO_TIERS`, etc.) or `burstable.html` (`CM_PLANS`).
