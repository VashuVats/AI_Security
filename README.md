# AI Security

A self-contained, static learning site for AI / LLM security, built around TryHackMe-style modules and hands-on labs.

| Page | What it is |
| --- | --- |
| [`index.html`](index.html) | **AI Security Field Manual**: the reference guide. Threat models, attack classes (prompt injection, jailbreaks, data and model poisoning, agent/tool abuse, supply chain, and more), defenses, and curated links to papers, frameworks and practice ranges. |
| [`attack-range.html`](attack-range.html) | **AI Attack Range**: an interactive learning and lab UI. Work through modules step by step, read the theory for each one, then try the matching lab. |

Both pages are single HTML files with inline CSS and JS. There is no build step and nothing to install.

## Run it

Open `index.html` or `attack-range.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/
```

It also works as-is on GitHub Pages (Settings > Pages > deploy from the `main` branch root).

## Screenshots

| Overview | Module theory | Lab in action |
| --- | --- | --- |
| ![Overview](screenshots/1-overview.png) | ![Module theory](screenshots/2-module-theory.png) | ![Lab](screenshots/3-lab-in-action.png) |

More views of the current design (light theme, phone layout, Field Manual) are in [`screenshots/redesign-v2/`](screenshots/redesign-v2/).

## Disclaimer

This material is for education and authorized security testing only. Only test systems you own or have explicit permission to assess.
