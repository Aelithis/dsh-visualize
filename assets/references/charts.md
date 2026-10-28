# Charts

Use self-contained SVG for charts and diagrams. Keep data, markup, styles, and
JavaScript inside the fragment. Remote libraries and fonts are blocked. Start
from ../examples/interactive-simulator.html or ../examples/comparison-chart.html.

- Prefer prose or a small table when it already answers the question.
- Compute domains from data with padding; label units and avoid overlapping ticks.
- Use a responsive viewBox and redraw data when controls change with dshViz.bind.
- Draw gridlines in --viz-grid, axes in --viz-axis, and series in --viz-series-N.
- Keep marks inside the plot area; clip paths that can escape.
- Encode series with labels and dash or marker shapes as well as color.
- Animate the entrance once, then update in place; respect prefers-reduced-motion.
- Use system fonts and at least 11px labels. No external script or stylesheet.
