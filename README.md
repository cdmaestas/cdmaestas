## Hi, I'm Chris 👋

**CTO for Data and AI Storage Solutions at IBM.** 25+ years architecting enterprise IT systems
across federal, commercial, and public sectors — with a focus on HPC, hybrid, and AI
infrastructure, and on unstructured data at scale: file, object, and tape storage across cloud,
on-premises, and edge environments.

The repos below are personal open-source work — tooling for large Linux clusters and IBM Storage
Scale: benchmarking harnesses, cluster administration, network validation, and install automation.

🔗 [cdmaestas.github.io](https://cdmaestas.github.io) · [LinkedIn](https://www.linkedin.com/in/chieftroublemakingofficer)

---

### Cluster tooling

**[Cbench](https://github.com/cdmaestas/cbench)** — Scalable cluster benchmarking and testing toolkit.
Automates the full HPC benchmarking lifecycle: generating job scripts, submitting them to the batch
scheduler, and parsing output into structured results across 31 benchmarks. Originally from Sandia
National Laboratories; v2 adds a modern Python toolchain alongside the original Perl.
`Perl` `Python`

**[CAP — Cluster Administration Package](https://github.com/cdmaestas/cap)** — Integrates, configures,
and manages HPC clusters by bundling common cluster tools (pdsh, genders, Slurm, munge, conman,
freeipmi, powerman) behind a unified build and install system with RPM and Debian packaging.
`Shell`

### IBM Storage Scale

**[Scale GUInstall](https://github.com/cdmaestas/Scale-GUInstall)** — A single-file web frontend for the
Storage Scale Installation Toolkit. Guided, form-driven install, deploy, and upgrade flows with a
command preview before anything executes. Ships as signed RPM and DEB packages.
`HTML` `Flask`

**[Network Readiness (KOET)](https://github.com/cdmaestas/StorageScale_NETWORK_READINESS)** — Development
fork of the Storage Scale network readiness tool. Validates interconnect latency, throughput, and packet
loss before a deployment goes near production.
`C`

**[Storage Scale MCP Server](https://github.com/cdmaestas/ibm-storage-scale-mcp-server)** — An MCP server
over the Storage Scale REST APIs and CLIs, letting LLMs query and interact with a live cluster through a
structured tool interface.
`Python`

**[ESS Comprestimator](https://github.com/cdmaestas/ess_comprestimator)** — Samples existing data to
project how much capacity compression would actually reclaim before you commit to enabling it.
`TypeScript`

---

<sub>The projects and views here are my own. They are not IBM products or services, and are neither
endorsed nor supported by IBM.</sub>
