# HeatnVector

Interactive chemical engineering learning site. The first lesson is a Bernoulli equation simulator with live controls for inlet speed, outlet diameter, inlet gauge pressure, and outlet elevation.

## Run locally

Open `index.html` in a browser. No build tools or dependencies are required.

## Publish with GitHub Pages

In the repository, open **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, then save. GitHub will show the published URL on that page after deployment. Updates to `main` will publish automatically.

## Model assumptions

The simulator uses steady, incompressible water flow, continuity through circular pipes, a constant density of 998 kg/m³, and gravity of 9.81 m/s². It ignores friction, pumps, and fittings. Pressure inputs and outputs are gauge pressures. The result is an educational idealization, not a pipe design calculation.
