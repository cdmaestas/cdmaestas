## Hi, I'm Chris 👋

**CTO for Data and AI Storage Solutions at IBM.** 25+ years architecting enterprise IT systems
across federal, commercial, and public sectors — with a focus on HPC, hybrid, and AI
infrastructure, and on unstructured data at scale: file, object, and tape storage across cloud,
on-premises, and edge environments.

The repos below are personal open-source work — tooling for large Linux clusters and IBM Storage
Scale: benchmarking harnesses, cluster administration, network validation, and install automation.

🔗 [cdmaestas.github.io](https://cdmaestas.github.io) · [LinkedIn](https://www.linkedin.com/in/chieftroublemakingofficer)

---

### Selected Recent Redbooks

- [IBM Storage Scale: Working with Abstract Data](https://www.redbooks.ibm.com/abstracts/sg248602.html?Open), IBM Redbooks (SG24-8602), 2026
- [IBM Storage Scale System 6000 with NVIDIA DGX SuperPOD Deployment Guide](https://www.redbooks.ibm.com/abstracts/redp5746.html?Open), IBM Redbooks (REDP-5746), 2026
- [IBM Storage Scale System Introduction Guide](https://www.redbooks.ibm.com/abstracts/redp5729.html?Open), IBM Redbooks (REDP-5729), 2026
- [IBM Storage Ceph Concepts and Architecture Guide](https://www.redbooks.ibm.com/abstracts/redp5721.html?Open), IBM Redbooks (REDP-5721), 2024
- [IBM Private, Public, and Hybrid Cloud Storage Solutions](https://www.redbooks.ibm.com/abstracts/redp4873.html?Open) (REDP-4873) and [IBM Software-Defined Storage Guide](https://www.redbooks.ibm.com/abstracts/redp5121.html?Open) (REDP-5121), IBM Redbooks, 2018

### Talks & Media

- [IBM Storage Scale: Working with Abstract Data](https://mediacenter.ibm.com/channel/IBM+Redbooks/194592493), Author Session, IBM MediaCenter, 2026
- [IBM Fusion Deep Archive and Tape Robotics for HPC and AI](https://www.youtube.com/watch?v=0W-NHF5d9tQ), SC25, 2025
- [Optimize Your Data Lifecycle](https://jeskell.com/optimize-your-data-lifecycle-join-our-digital-talk-series-with-ibm-storage-scale-tape/), Jeskell digital talk series, 2025
- [Roundtable: High Performance Storage](https://www.youtube.com/watch?v=4s8Lq1UuKPo) (with Patano, Atzkern, Coomer), 2024
- [Revamping Data Storage to Harness AI](https://siliconangle.com/2023/07/27/revamping-data-storage-to-harness-ai-for-an-information-supply-chain-ibmstoragesummit/), theCUBE at IBM Storage Summit, 2023
- [IBM Storage at Storage Field Day 25](https://techfieldday.com/appearance/ibm-storage-presents-at-storage-field-day-25/), Tech Field Day, 2023
- [IBM TechU 2021: IBM Storage Portfolio for Data and AI](https://mediacenter.ibm.com/media/IBM+TechU+2021+virtual+edition+-+IBM+Storage+portfolio+can+address+Data+and+AI+with+Chris+Maestas/1_m77bd1yb), 2021
- [Spectrum Scale User Group (SSUG)](https://www.spectrumscaleug.org/presentations/) presenter, various sessions, 2018–2025

### Blog Posts

- [CAS for Scale System 6000](https://community.ibm.com/community/user/blogs/christopher-maestas/2026/05/30/cas-for-scale-system-6000), IBM Community, 2026
- [HPC, AI and Culture: My Trip to SCAHPC Asia 2026](https://community.ibm.com/community/user/blogs/christopher-maestas/2026/02/06/hpc-ai-and-culture-my-trip-to-scahpc-asia-2026), IBM Community, 2026
- [Visit to Copernicus LAC Chile](https://es.linkedin.com/posts/copernicuslacchile_ayer-recibimos-en-copernicuslac-chile-a-christopher-activity-7435316350891384833-QA1R), LinkedIn, 2026

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

**[dool](https://github.com/cdmaestas/dool)** — Command-line, real-time monitoring of Linux system
resources (CPU, memory, network, disk, load) with a plugin architecture. Forked from
[scottchiefbaker/dool](https://github.com/scottchiefbaker/dool), a Python 3 successor to dstat.
`Python` `fork`

### IBM Storage Scale

**[Scale GUInstall](https://github.com/cdmaestas/Scale-GUInstall)** — A single-file web frontend for the
Storage Scale Installation Toolkit. Guided, form-driven install, deploy, and upgrade flows with a
command preview before anything executes. Ships as signed RPM and DEB packages.
`HTML` `Flask`

**[Network Readiness (KOET)](https://github.com/cdmaestas/StorageScale_NETWORK_READINESS)** — Validates
interconnect latency, throughput, and packet loss before a deployment goes near production. Forked from
[IBM/SpectrumScale_NETWORK_READINESS](https://github.com/IBM/SpectrumScale_NETWORK_READINESS).
`C` `fork`

**[Storage Scale MCP Server](https://github.com/cdmaestas/ibm-storage-scale-mcp-server)** — An MCP server
over the Storage Scale REST APIs and CLIs, letting LLMs query and interact with a live cluster through a
structured tool interface. Forked from
[IBM/ibm-storage-scale-mcp-server](https://github.com/IBM/ibm-storage-scale-mcp-server).
`Python` `fork`

**[Storage Scale Agents](https://github.com/cdmaestas/ibm-storage-scale-agents)** — Specialized reference
AI agents built on the Storage Scale MCP server, giving LLMs task-focused ways to operate against a live
cluster. Forked from [IBM/ibm-storage-scale-agents](https://github.com/IBM/ibm-storage-scale-agents).
`Python` `fork`

**[GPFS User Group Tools](https://github.com/cdmaestas/gpfsug-tools)** — Community-maintained tools from the
Spectrum Scale (GPFS) User Group for administering and inspecting GPFS / Storage Scale clusters. Forked from
[gpfsug/gpfsug-tools](https://github.com/gpfsug/gpfsug-tools).
`C` `fork`

**[ESS Comprestimator](https://github.com/cdmaestas/ess_comprestimator)** — Samples existing data to
project how much capacity compression would actually reclaim before you commit to enabling it. Forked from
[IBM/ess_comprestimator](https://github.com/IBM/ess_comprestimator).
`TypeScript` `fork`

---

<sub>The projects and views here are my own. They are not IBM products or services, and are neither
endorsed nor supported by IBM.</sub>
