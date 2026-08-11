# Arjun Krishna B — GitHub Profile

Animated portfolio README that matches the **PORTFOLIO — INDEX N° 001** design language.
All charts and diagrams are inline animated SVGs (SMIL + CSS keyframes) — no external image hosts, no JavaScript dependency.

---

## Files

| file | purpose |
|------|---------|
| `README.md`        | The actual GitHub profile content. Drop into `<your-username>/<your-username>` repo as `README.md`. |
| `preview.html`     | Standalone HTML preview that renders the same content with the design's full typography. Open in a browser. |
| `INSTALL.md`       | This file. |

---

## How to install on GitHub

1. Create a **new repository** with the **same name as your GitHub username**.
   Example: if your handle is `arjun80892`, the repo must be `arjun80892/arjun80892`.
2. Check **"Add a README file"** when creating.
3. Replace the generated `README.md` with the one in this folder.
4. Commit. Your profile page at `github.com/<your-username>` will render the README.

> GitHub renders inline SVG with both SMIL (`<animate>`) and CSS keyframe animations. No build step required.

---

## What animates

| section | animation |
|---------|-----------|
| Hero name  | Blinking caret (terminal-style) |
| System map | Connection lines draw in · satellite nodes fade in · live status dots pulse |
| Telemetry / bar chart   | Bars grow from 0 to value · percent labels fade in |
| Telemetry / line chart  | Line draws in via stroke-dashoffset · data points pop · halos pulse |
| GitHub stats box        | Rows slide up sequentially |
| Languages by repository | Bars grow with stagger |
| Contribution telemetry  | Line draws in · peak point pulses |
| The route (timeline)    | Track draws in · stops fade up sequentially · halos pulse |

Total wall-clock animation: ~2 seconds, then static (or in the case of the pulses, infinite gentle loops).

---

## Tech notes

- All fonts: `JetBrains Mono` / `ui-monospace` (graceful fallback to system mono).
- Color palette: `#000` on `#fff`. No grays except very subtle `#555` for secondary text and `#eee` for grid lines.
- Inline SVGs use `viewBox` for responsiveness — no fixed pixel widths in the SVGs themselves.
- GitHub strips `<script>` tags but allows `<style>` and SMIL — the profile is fully static after load.

---

## Customising

Everything is plain markdown + inline SVG — search for the relevant section heading (`## 01 / JOB-SHIELD`, `### 2026`, etc.) and edit the text content. Bar chart percentages are in `<animate attributeName="width" from="0" to="..." />` — change the `to` value to retune.
