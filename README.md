<img src="fox.jpg" alt="A red fox on a snow-covered ridge" width="100%">

I work on high-speed and RF hardware for datacenters and photograph wildlife on
weekends. I write software for both, and more recently for working with
language models. These are my public projects.

**[EE Labs](https://github.com/reedos/ee-labs)**: interactive labs for learning
circuits, signals and control, [live here](https://reedos.github.io/ee-labs/).
The four live labs hold 153 experiments and lessons, from Kirchhoff's laws and
circuit elements through filters, DSP and feedback control. Changing a parameter
updates every view at once, and each number on screen shows where it came from.
I built them because I enjoy the math behind these systems. The labs share
their underlying code, so a filter built in Circuit Lab opens in Signal Lab with
the same resonance and Q, and every claim in a lab's notes is checked by a test.

**[RF Lab Reference](https://github.com/reedos/rf_lab_reference)**: eight
calculators for RF bench work, designed for a phone or tablet next to a VNA,
[live here](https://reedos.github.io/rf_lab_reference/). They cover power and
voltage conversion, impedance matching on a Smith chart, return loss and VSWR,
mixed-mode S-parameters, large-signal behavior, sweep planning, cascaded power
and noise, and electrical delay. Each one shows its equations with your numbers
substituted, and everything is calculated in the browser, with no backend.
Settings are saved in the page link, so a setup can be bookmarked or shared.

**[Gradient Ascent](https://github.com/reedos/gradient_ascent)**: a guide to
working with language models,
[live here](https://reedos.github.io/gradient_ascent/). It covers 49 techniques
in eight levels, ordered by how much the model decides on its own, from
answering a single question to running as an independent agent. Each page
explains how the technique works, what it costs and when a simpler one is
enough. The 66 short examples behind the pages run offline against a stub
model, with no API key needed. The site is still in development: the pages are
based on primary sources, and results from real model runs have not been added
yet.

**[Stack Ledger](https://github.com/reedos/stack_ledger)**: a public research
ledger of the AI buildout, [live here](https://reedos.github.io/stack_ledger/).
It tracks five layers (energy, chips, infrastructure, models and applications)
and separates capacity that has been built and delivered from what has only
been announced. Every event and observation carries an evidence grade from A
(official statistics and filings) to D (unverified claims), set by its source
rather than by a model, and unconfirmed reports stay out of the charts. It draws
on public data from sources including the IEA, DOE, Epoch AI, BLS and the Census
Bureau, and the ledger can be downloaded as CSV or JSON. A model running locally
on my PC drafts research daily, and nothing it proposes is published without
passing validation and an evidence screen.

**[Field Catalog](https://github.com/reedos/field-catalog)**: a Windows desktop
app for culling and cataloging wildlife photos, with an installer on the
[releases page](https://github.com/reedos/field-catalog/releases). It imports a
card without moving the originals, and you cull with the keyboard as you would
in Lightroom. A burst opens with every frame on screen and pan and zoom synced
across them. It can identify species with a local vision model or an API key,
and keeps a life list and a map of where you shot. Rejecting a photo only marks
it; deleting files is a separate step with a dry run. It runs locally and
uploads nothing unless you choose to.
