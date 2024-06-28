# Synapse-ThreatFox
This Synapse Rapid Power-up adds support for enriching observables using [ThreatFox](https://threatfox.abuse.ch/) as well as ingesting IOCs recently reported on the platform.

---
## Usage
There are 5 commands available: 
- `ex.threatfox.ingest.indicators`
    - Ingest recently reported indicators
- `ex.threatfox.ingest.indicators`
    - Ingest all malware profiles from ThreatFox
- `ex.threatfox.enrich`
    - Enrich inbound nodes using the ThreatFox API
- `ex.threatfox.search`
    - Search the ThreatFox database for a user-defined string

- `ex.threatfox.setup.tagprefix`
    - Setup Threatfox tag prefix

---
## Installation
The easiest way to use this Power-Up is to load the JSON package into the Cortex by running: 

`pkg.load --raw "https://raw.githubusercontent.com/EXC3L-ONE/synapse-threatfox/main/synapse_threatfox.json"`

Alternatively, you can also clone this repo, and load the package via `python -m synapse.tools.genpkg` (see reference in Synapse docs [here](https://synapse.docs.vertex.link/en/latest/synapse/userguides/syn_tools_genpkg.html#building-the-example-package))
