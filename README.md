<img src="fox.jpg" alt="A red fox on a snow-covered ridge" width="100%">

I'm a datacenter hardware engineer specializing in high-speed and RF, and a
wildlife photographer on weekends. The projects below come from both, and from
my interest in how AI is used and what it takes to build it.

**[EE Labs](https://github.com/reedos/ee-labs)**: 153 interactive experiments
and lessons across four labs, covering circuit laws, filters, DSP and feedback
control, [live here](https://reedos.github.io/ee-labs/). I built them because I
love the math behind these systems. Change a parameter and every view updates
together, with each number showing where it came from. Circuit Lab can hand a
filter to Signal Lab with the same resonance and Q. Every claim in the notes is
measured by an automated test, and the site does not deploy unless the tests
pass.

**[RF Lab Reference](https://github.com/reedos/rf_lab_reference)**: eight
calculators I keep open beside the VNA, built for a phone or tablet,
[live here](https://reedos.github.io/rf_lab_reference/). They cover power and
voltage conversion, Smith chart matching with return loss and VSWR, mixed-mode
S-parameters, IP3 and P1dB, sweep planning, cascaded power and noise, and
electrical delay. Each one shows the full calculation with your numbers
substituted. There is no backend server, and each setup is saved in its link
so you can bookmark or share it.

**[Gradient Ascent](https://github.com/reedos/gradient_ascent)**: a guide to
working with language models,
[live here](https://reedos.github.io/gradient_ascent/). It organizes 49
techniques into eight levels by how much the model decides on its own. Every
page covers how the technique works, what it costs and when something simpler
will do, with 66 runnable examples behind the pages. The RAG and agentic RAG
pages carry measured results from real runs on a local 30B-class model; the
rest are written from primary sources and marked illustrative until they are
measured.

**[Stack Ledger](https://github.com/reedos/stack_ledger)**: a public research
ledger of what the AI buildout actually delivers across energy, chips,
infrastructure, models and applications,
[live here](https://reedos.github.io/stack_ledger/). It separates built capacity
from announcements and grades every event and observation from A (official
filings and statistics) to D (unverified claims). The source sets the grade,
never a model, and unconfirmed reports stay out of the charts. Sources include
the IEA, DOE, Epoch AI, BLS and the Census Bureau, and the whole ledger
downloads as CSV or JSON. A model on my own PC researches it daily, and its
findings are published only after passing validation and an evidence screen.

**[Field Catalog](https://github.com/reedos/field-catalog)**: a Windows app for
culling and cataloging wildlife photos, with an installer on the
[releases page](https://github.com/reedos/field-catalog/releases). Import a card
without moving the originals, cull from the keyboard the way you would in
Lightroom, and compare an entire burst on one screen with pan and zoom synced.
It can identify species with a local vision model or an API key, and it keeps
your life list and maps where you shot. Rejecting a photo only marks it;
deleting files is a separate step behind a dry run. It runs locally, with no
account, cloud service or telemetry.
