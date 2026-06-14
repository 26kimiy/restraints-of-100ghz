# Restraints of 100 GHz

An interactive, single-page explainer on why measuring and moving a 100 GHz signal is so hard, and how it ties into optical interconnects.

Prepared by Kimi Yashar for Ali Khalatpour (Piris Labs). Built with Claude.

## View it
- **index.html** — the main report. Open it in any browser, or turn on GitHub Pages (repo Settings → Pages → deploy from `main`) and it serves at `https://<your-username>.github.io/<repo-name>/`.
- **backside.html** — a study copy with hover-to-define tooltips on the jargon.

No build step and no dependencies; all math, charts, and simulations run inside the single HTML file.

## What's inside
- An oscilloscope view of how a clean signal degrades as frequency climbs
- "Difficulty with 100 GHz" — a rotating-cube walkthrough of each effect (skin effect, dielectric loss, phase noise, moding, ...), each with an improvement and the range it works in
- A live skin-effect cross-section, a copper-lattice thermal simulation, and a power-gap diagram
- Alternatives to copper as a high-to-low frequency timeline, including lasers (diode laser + terahertz QCL)
- A "Frequencies around us" explorer with an IEEE band key
- References (29 cited sources) plus the videos used

Physics is exact where computed and labelled illustrative where modelled; every factual claim links to the References tab.
