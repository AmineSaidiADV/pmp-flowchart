# PMP PMBOK 6th Edition — Interactive Reference

A fully offline, single-file interactive reference tool for the **PMP® exam (PMBOK® Guide 6th Edition)**. No build step, no server, no dependencies beyond a browser and an internet connection for the flowchart view (D3.js CDN).

> **Live:** open `index.html` directly in any modern browser.

---

## Features

| Tab | Description |
|---|---|
| **Flow Chart** | D3.js force-directed graph of all 49 processes with zoom/pan, filter by Process Group or Knowledge Area, milestone badges, and an ITTO detail panel |
| **ITTO Matrix** | Cross-reference grid showing which artifacts appear as inputs and/or outputs across all processes |
| **Timeline** | Processes laid out in a Gantt-style grid by Process Group phase |
| **Knowledge Areas** | Accordion by Knowledge Area — expand to see every process with full ITTO detail |
| **Tools** | 75+ PMBOK tools with SVG diagrams, exam tips, and "when to use" notes |

### Interaction
- Click any process node to open the **ITTO detail panel** (inputs, tools, outputs with explanations and examples)
- Click any Tool & Technique item to see an inline explanation — if a matching tool card exists, a **"See full tool card →"** button opens a modal with the full diagram
- Filter by Process Group, Knowledge Area, or free-text search
- Light / Dark mode toggle

---

## Usage

```bash
# Clone
git clone https://github.com/AmineSaidiADV/pmp-flowchart.git
cd pmp-flowchart

# Open directly — no server needed
open index.html         # macOS
start index.html        # Windows
xdg-open index.html     # Linux
```

The flowchart view loads D3.js from `d3js.org` CDN — all other views work fully offline.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Structure | Pure HTML5 (single file) |
| Styling | CSS custom properties (dark theme) |
| Interactivity | Vanilla JavaScript (ES6+) |
| Flowchart | [D3.js v7](https://d3js.org/) via CDN |
| Diagrams | Inline SVG (no images) |

---

## Screenshot

> Flow Chart view with ITTO panel open and milestone strip visible.

---

## Disclaimer

This tool is an **unofficial study aid** and is not affiliated with, endorsed by, or sponsored by PMI®. PMBOK® is a registered trademark of the Project Management Institute.

All process data is based on the **PMBOK® Guide — Sixth Edition**.

> **Accuracy notice:** While every effort has been made to ensure the ITTO data, tool descriptions, and process details are correct, this tool may contain errors or omissions. Always cross-reference with the official PMBOK® Guide before your exam. If you spot a mistake, please [open an issue](https://github.com/AmineSaidiADV/pmp-flowchart/issues) so it can be corrected for everyone.

---

## License

MIT © [Amin Saidi](https://github.com/AmineSaidiADV)

---

## Contributing

Issues and pull requests are welcome. If you spot an error in the ITTO data or want to improve a tool visual, open an issue or submit a PR.
