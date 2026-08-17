## Hi, I'm Rahul

Fifteen years in production software, ten of them at Innovaccer on clinical data
platforms. Now independent, consulting on data and AI, and building in the open.

Most of what I build turns out to be the same problem in a new language: move something through a
pipeline you can still inspect afterwards. Started with messages off a Redis queue in 2017, ended up
with a grounding layer that has to justify why it cleared a finding.

### Active

**[Lithrim CE](https://github.com/lithrim-dev/lithrim)** (Apache-2.0)
Evaluation harness for agentic AI. A configurable LLM judge council sitting over a deterministic
grounding layer, where a flag stands unless a machine-checkable authority positively disproves it,
and an unresolved check never clears anything. Every grade writes an immutable record with the
configuration hashed into a signature, so a past result reproduces from storage with no model call.
Study on [Zenodo](https://doi.org/10.5281/zenodo.21270267), preregistered on OSF. The rerun rejected
three of my four predictions and I published that as a new version.

**[ETLP](https://github.com/etlp-clj)**
Clojure data-pipeline library built on transducers and core.async. Protocol-based connector
contract, DAG executor, workflow DSL, and a streaming HL7v2 parser. Written as a side project in
2020, then it turned out to solve a production ingestion problem and went to work.

**[Zyng](https://zyng.work)**
Turns a product into an editable walkthrough or launch film. Live and self-serve.

### Not live

[Mapify](https://github.com/aregee/mapify-io) was an agentic UI over low-code data transformation, an attempt to package ETLP so a data
engineer could drive it without writing the transform by hand. It is not running. Part of that work
became Lithrim's ingestion layer.

I build things fast and I am not precious about killing them. The parts tend to come back.

### Writing and talks

- [Breaking Down the Last Monolith: Micro Frontends](https://dev.to/aregee/breaking-down-the-last-monolith-micro-frontends-hd4).
- [Lamdba Calculus](https://github.com/aregee/lambdajs)
- Technical reviewer on *The Art of MicroFrontends*, first edition.
#### Talks: 
- [AI evaluation architecture (Dubai, 2026)](https://dubai.aitinkerers.org/talks/rsvp_e3czbFAtNPA) 
- [micro-frontend runtime and migration (JSFoo)](https://youtu.be/VMGmgwYNmQY?si=-jcxZ6lk0ZXq-WQk),
- [real-time push with Python, Gevent, Redis and Nginx (PyDelhi, 2017)](https://github.com/aregee/teteris.py/blob/master/pitch.pdf).

rahul.nbg@gmail.com
