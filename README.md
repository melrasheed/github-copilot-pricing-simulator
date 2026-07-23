# GitHub Copilot Usage-Based Billing Simulator

An offline, browser-based **educational simulator** that teaches how GitHub Copilot
usage-based billing, budgets, and spending controls work.

**▶ Live site:** https://melrasheed.github.io/github-copilot-pricing-simulator/

## About

The entire app is a single, self-contained `index.html` — no build step, no CDN,
no network calls. It works fully offline and is hosted on GitHub Pages.

Features:

- **Overview** — shared AI credit pool, seats, and current-cycle spend at a glance.
- **Configuration** — mirrors GitHub's Billing &amp; Licensing UI: Budgets and alerts
  (with a GitHub-style "New budget" modal), Cost centers, Licensing, Policies, and
  documented Scenario presets.
- **Simulator** — run a billing cycle, watch budgets, alerts (75/90/100%), and hard
  stops trigger, and time-travel to the next cycle.
- **Alerts &amp; Reports** — usage breakdowns with CSV/JSON exports.
- **Documentation** — rules (R1–R18), exclusions, and traceability back to the
  official [GitHub billing docs](https://docs.github.com/en/billing).

## Usage

Just open `index.html` in any modern browser, or visit the live site above.

## Disclaimer

This is an **unofficial, independent educational tool**. It is **not affiliated
with, endorsed by, or supported by Microsoft or GitHub**, and **neither Microsoft
nor GitHub is responsible** for this tool or its content. Credit values,
promotions, and rules are modeled from public GitHub documentation and may be
inaccurate or out of date. Always consult the
[official GitHub billing documentation](https://docs.github.com/en/billing) for
authoritative, current information.

**Last updated:** 2026-07-23
**Issues or feedback:** mohdrash1990@hotmail.com
