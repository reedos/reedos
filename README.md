<img src="fox.jpg" alt="A red fox on a snow-covered ridge" width="100%">

I'm a datacenter hardware engineer, mostly high-speed and RF, and I spend a lot
of weekends photographing wildlife. Lately I've gotten pretty excited about AI
too, both what it could do and the infrastructure being built for it. Here's
what I've made public.

**[EE Labs](https://github.com/reedos/ee-labs)** came out of loving the math
behind circuits, signals and control. There are four interactive labs now, with
153 experiments and lessons ([live here](https://reedos.github.io/ee-labs/)).
When you change a parameter, the plots and numbers update together, and each
number shows where it came from. Circuit Lab can even hand a filter to Signal
Lab with the same resonance and Q. Automated tests check the explanations, and
the site won't deploy if one of them fails.

**[RF Lab Reference](https://github.com/reedos/rf_lab_reference)** is what I
keep open on my phone at the VNA. It has eight calculators, for power and
voltage conversion, Smith chart matching, mixed-mode S-parameters, IP3 and P1dB,
sweep planning, cascaded noise and electrical delay, and each one shows the math
with your numbers in it. Nothing runs on a server, and the link saves the whole
setup. ([Calculators here.](https://reedos.github.io/rf_lab_reference/))

**[Gradient Ascent](https://github.com/reedos/gradient_ascent)** is my guide to
working with language models ([live here](https://reedos.github.io/gradient_ascent/)).
It covers 49 techniques in eight levels, grouped by how much the model decides
on its own, and each page explains how the technique works, what it costs and
when something simpler would do. There are also 66 examples you can run
yourself. It's still in progress. The RAG and agentic RAG pages have measured
results from runs on a local 30B-class model, and the other pages are written
from primary sources for now.

I started **[Stack Ledger](https://github.com/reedos/stack_ledger)** because I
wanted to know what the AI buildout is actually delivering. It tracks energy,
chips, infrastructure, models and applications, and grades each event and
observation on its evidence. An A means an official filing or statistic backs it
up, and a D means it hasn't been verified. Unconfirmed reports don't go on the
charts. Sources include the IEA, DOE, Epoch AI, BLS and the Census Bureau, and
the ledger can be downloaded as CSV or JSON. A model on my PC does research for
it every day, and what it finds goes up only after passing validation and an
evidence check. ([See the ledger.](https://reedos.github.io/stack_ledger/))

**[Field Catalog](https://github.com/reedos/field-catalog)** is the Windows app
I cull and catalog my wildlife photos with. You import a card without moving the
originals, cull with the same keys as Lightroom, and compare a whole burst side
by side with pan and zoom synced, which makes it easy to see which frame is
sharp. It can also identify species with a local vision model or an API key,
keep a life list, and show on a map where you shot. Rejecting a photo only marks
it. Deleting files is a separate step, with a dry run first. The installer is on
the [releases page](https://github.com/reedos/field-catalog/releases).
