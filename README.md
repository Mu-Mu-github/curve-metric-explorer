# Curve-metric explorer II

Eight interactive teaching pages on the criteria that published benchmarks use to score curve
digitization (how well a program turns a picture of a graph back into numbers). Built by
Qiaomu Yang (Manthiram Lab, Caltech) in October 2026 for a lab-notebook report. Every page
runs on its own in a browser; nothing is installed and no data leaves the browser.

All curves are synthetic, made for teaching. The metrics are teaching implementations of the
published definitions, not the official scoring code of any benchmark.

| Page | What it shows |
|---|---|
| `index.html` | Start page: the eight figures, the criteria most benchmarks share, references |
| `fig1-pipeline.html` | The six decisions behind every curve score; pick a benchmark to see its path |
| `fig2-pairing.html` | Pairing digitized curves with true curves: recall, precision, swapped labels at a crossing |
| `fig3-line-error.html` | Line plots on a shared grid under four divisors: the value, the y-range, the chart maximum, the minor tick |
| `fig4-scatter.html` | Scatter plots: hits within a tolerance, the hit rate against the tolerance |
| `fig5-calibration.html` | Pixels before values: tick, pixel and value scores when an anchor or a label is wrong |
| `fig6-benchmark.html` | Twenty figures at once: output success, trusted usability, FPC-NRMSE |
| `fig7-loops.html` | A cyclic voltammogram: why vertical error fails; Fréchet, ECS and a tolerance band |
| `fig8-scorecard.html` | One digitization, every criterion: seven switchable defects against a two-annotator noise floor |

`embed/` holds a compact version of each page (the interactive panel only, with a bar that
links to the full page). These are the panels framed in the Notion report; each opens in the
state the report's figure caption describes. Add `#focus=0` to an embed URL to show the
explanation inside the frame, or a hash such as `#off=0.2` to start from another state.
