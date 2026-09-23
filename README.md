<img src="fox.jpg" alt="A red fox on a snow-covered ridge" width="100%">

I work on high-speed and RF hardware for datacenters during the week and
photograph wildlife on the weekends. Both keep turning into software: something
needs measuring, simulating or sorting, and nothing off the shelf quite fits.
Language models have become part of how I build, so two of the projects are
about them: how to work with them, and what the AI buildout is actually
delivering.

Some of what I build stays on my own machine. These are the public projects.

**[EE Labs](https://github.com/reedos/ee-labs)** — interactive labs for learning
how circuits, signals and control behave,
[live here](https://reedos.github.io/ee-labs/). Four labs run from Kirchhoff's
laws and circuit elements through filters, DSP and feedback. I built them
because I like the math underneath and the way it connects: an RLC network, a
digital biquad and a plant in a feedback loop are the same object in three
vocabularies, so a filter designed in Circuit Lab opens in Signal Lab with the
same resonance and Q. Every explanatory sentence is a claim about physics, and
a test has to measure it before the app is allowed to show it.

**[RF Lab Reference](https://github.com/reedos/rf_lab_reference)** — calculators
for a phone or tablet beside the VNA,
[live here](https://reedos.github.io/rf_lab_reference/): power and voltage
conversions, Smith chart matching with return loss and VSWR, mixed-mode
S-parameters, large-signal behavior, sweep planning, cascaded power and noise,
and electrical delay. Every calculator shows its work, and a setup lives in the
link rather than on the device.

**[Gradient Ascent](https://github.com/reedos/gradient_ascent)** — a guide to
working with language models,
[live here](https://reedos.github.io/gradient_ascent/). It covers forty-nine
techniques in eight levels, ordered by how much the model decides for itself,
from a single question to agents that run on their own. Each page shows how the
technique works, what it costs and when a simpler one is enough, with a
runnable example behind it, and the home page has one starting point for people
new to AI and another for people building with it. It is still in development:
the pages are written from primary sources, and measured results from real runs
come next.

**[Stack Ledger](https://github.com/reedos/stack_ledger)** — a public research
ledger of the AI buildout across five layers: energy, chips, infrastructure,
models and applications, [live here](https://reedos.github.io/stack_ledger/). I
want to know what the buildout delivers in power, skilled jobs, local investment
and useful work, so the ledger separates announcements and forecasts from
measured progress, and every event and observation carries an evidence grade. A
model running on my own PC researches updates each day, and nothing publishes
until it passes validation and an evidence check.

**[Field Catalog](https://github.com/reedos/field-catalog)** — a Windows desktop
app for photographers who come home with more frames than time. Compare a burst
frame by frame, keep the one that works and let the rest go. It can identify the
species with a local vision model or an API key, keeps a life list and maps
where you shot. Nothing leaves your machine unless you ask it to.
