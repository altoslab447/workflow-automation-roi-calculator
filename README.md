# AI Agent Cost And ROI Calculator

A browser-only planning tool from Altos Lab for estimating whether an AI
workflow automation sprint is worth exploring.

The calculator estimates:

- gross labor savings,
- human review cost,
- rework buffer,
- AI operating cost,
- net monthly savings,
- breakeven build budget.

It is intentionally simple and private by default: no backend, no login, no
cookies, no wallet connection, and no analytics script in this version.

## Why This Exists

AI automations are easy to overbuild. This tool gives founders and operators a
quick way to decide whether a repeated workflow has enough measurable payback
to justify a pilot.

## Local Preview

```bash
python3 -m http.server 8787
```

Then open:

```text
http://127.0.0.1:8787/index.html
```

## Pages

- `index.html`: calculator
- `about.html`: model explanation
- `privacy.html`: privacy and data-handling notes
- `contact.html`: workflow audit request template

## Studio

Built by Altos Lab, an AI automation and product engineering studio.
