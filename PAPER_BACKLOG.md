# Paper Backlog and Non-Core References

Last audited: 2026-07-26

This document preserves papers that were seriously considered for the Awesome Agentic Commerce collection but are not currently in the core `README.md`. Exclusion from the public list does not imply low quality. Common reasons include overlap with a stronger representative work, weak direct connection to delegated commerce, immature publication status, or the need to keep the historical foundations compact.

Before moving any item into the core list, recheck its abstract, publication status, venue, official URL or DOI, and fit with the current taxonomy.

## Strong References for Survey Writing

These works are valuable citations for the journal survey, but the public Awesome list already contains enough representative papers from the same technical line.

| Work | Status | Theme | Why It Is Not in the Core List | Reconsider When |
|---|---|---|---|---|
| [Commitment Machines](https://doi.org/10.1007/3-540-45448-9_17) | ATAL 2001 / LNAI 2002 | Commitment-based interaction protocols | Overlaps with the retained AAMAS 2002 flexible-protocol paper. | A dedicated protocol-evolution subsection needs an earlier starting point. |
| [Tosca: Operationalizing Commitments Over Information Protocols](https://www.ijcai.org/proceedings/2017/37) | IJCAI 2017 | Executable commitment protocols and alignment | Excellent modern continuation of the commitment line, but adding every step would make the compact foundations too granular. | The survey explicitly develops the sequence from commitment semantics to executable and verifiable protocols. |
| [Review on Computational Trust and Reputation Models](https://doi.org/10.1007/s10462-004-0041-5) | Artificial Intelligence Review 2005 | Trust and reputation survey | Redundant with retained concrete trust models and the later review below. | A historical comparison of early trust-model taxonomies is required. |
| [Computational Trust and Reputation Models for Open Multi-Agent Systems: A Review](https://doi.org/10.1007/s10462-011-9277-z) | Artificial Intelligence Review 2013 | Open-MAS trust and reputation survey | Highly useful for paper writing and for studying the target journal, but target-venue fit alone is not a public Awesome inclusion criterion. | The public list adds a dedicated survey subsection or the paper needs a single comprehensive trust taxonomy reference. |
| [Flexible Double Auctions for Electronic Commerce: Theory and Implementation](https://doi.org/10.1016/S0167-9236(98)00060-8) | Decision Support Systems 1998 | Double auctions and mechanism design | Closely tied to the retained Michigan AuctionBot system; the Awesome list keeps one representative public-marketplace entry. | Mechanism-design coverage becomes more important than system-history coverage. |
| [The 2001 Trading Agent Competition](https://doi.org/10.1080/1019678032000062212) | Electronic Markets 2003 | Trading-agent competition and market evaluation | A useful historical case, but less foundational than the retained AMEC surveys and marketplace architecture papers. | The survey develops a historical benchmark or competition lineage. |
| [WASP: Benchmarking Web Agent Security Against Prompt Injection Attacks](https://proceedings.neurips.cc/paper_files/paper/2025/hash/1c9818387f5dd0a0bc151214660f059d-Abstract-Datasets_and_Benchmarks_Track.html) | NeurIPS 2025 Datasets and Benchmarks | Web-agent prompt-injection security | High quality but domain-general; Agent Security Bench and WebDecept provide sufficient broad and commerce-specific coverage. | A security-benchmark comparison requires a second end-to-end web-agent benchmark. |
| [WebRollback: Rolling Back Web Agent Failures](https://aclanthology.org/2026.eacl-short.12/) | EACL 2026 Short Paper | Web-agent rollback and recovery | Technically relevant to recourse, but not commerce-specific. | Rollback is connected experimentally to checkout, cancellation, refund, or other commercial actions. |
| [Stateful Least Privilege Authorization for the Cloud](https://www.usenix.org/conference/usenixsecurity24/presentation/cao-leo) | USENIX Security 2024 | Stateful authorization and least privilege | Strong authorization foundation, but centered on general cloud/OAuth security rather than commerce agents. | The survey needs a formal authorization baseline beyond authenticated delegation. |

## Historical Candidates Removed During Compression

These entries appeared in an earlier, more expansive version of the historical foundations and were removed when nine small sections were merged into five compact sections.

| Work | Status | Theme | Why It Was Removed |
|---|---|---|---|
| [Multiagent Systems: A Survey from a Machine Learning Perspective](https://doi.org/10.1023/A:1008942012299) | Autonomous Robots 2000 | Learning in multi-agent systems | Broad survey; the retained MARL survey and MAS foundations book cover the necessary backbone. |
| [Agent Communication Languages: The Current Landscape](https://doi.org/10.1109/5254.757631) | IEEE Intelligent Systems 1999 | Agent communication languages | Redundant with the retained KQML paper and FIPA ACL standard. |
| [FIPA Contract Net Interaction Protocol Specification](https://www.fipa.org/specs/fipa00029/SC00029H.html) | FIPA Standard 2002 | Contract Net protocol standard | Redundant with the original Contract Net paper and the retained FIPA ACL message standard. |
| [Issues in Automated Negotiation and Electronic Commerce: Extending the Contract Net Framework](https://aaai.org/papers/icmas95-044-issues-in-automated-negotiation-and-electronic-commerce-extending-the-contract-net-framework/) | ICMAS 1995 | Automated negotiation for e-commerce | Superseded in the compact list by the more influential negotiation-functions paper and negotiation survey. |
| [ANEGMA: An Automated Negotiation Model for E-Markets](https://doi.org/10.1007/s10458-021-09513-x) | Autonomous Agents and Multi-Agent Systems 2021 | Automated negotiation for e-markets | Relevant but represents one specific model rather than a necessary historical anchor. |
| [Trust Management Through Reputation Mechanisms](https://doi.org/10.1080/08839510050144868) | Applied Artificial Intelligence 2000 | Reputation mechanisms | Replaced by the more directly e-commerce-focused distributed reputation paper. |
| [An Evidential Model of Distributed Reputation Management](https://doi.org/10.1145/544741.544809) | AAMAS 2002 | Distributed reputation | Overlaps with the retained journal article on distributed reputation management for electronic commerce. |
| [Dimensions of Adjustable Autonomy and Mixed-Initiative Interaction](https://doi.org/10.1007/978-3-540-25928-2_3) | LNAI 2004 | Adjustable autonomy | Useful general HAI foundation, but less commerce-specific than the retained mixed-initiative and delegation-interface papers. |

## Monitor for Publication or Maturity

These works are directly relevant or potentially valuable, but should not yet carry the same weight as peer-reviewed or mature benchmark research.

| Work | Current Status | Theme | Current Concern | Reconsider When |
|---|---|---|---|---|
| [PayBench: A Benchmark for Unsafe Commercial Autonomy in AI Agents with Delegated Payment Authority](https://paybench.org/) | Independent benchmark project, 2026 | Delegated payment safety | Highly relevant, but currently independent, not peer reviewed, not archived on arXiv, and presented partly as a roadmap. | A stable dataset, complete results, archival preprint, or formal venue is available. |
| [Whispers of Wealth: Red-Teaming Google's Agent Payments Protocol](https://arxiv.org/abs/2601.22569) | arXiv 2026 | Agent-payment protocol security | Timely but currently a preprint and closely tied to one protocol. | Formally accepted, materially expanded, or independently replicated. |
| [SoK: Security of Autonomous LLM Agents in Agentic Commerce](https://arxiv.org/abs/2604.15367) | arXiv 2026 | Agentic-commerce security systematization | Scope is highly relevant, but publication status and authority are not yet sufficient for a core survey anchor. | Accepted at a recognized security, agents, or AI venue. |

## E-Commerce Work Outside the Agentic Core

These papers are useful e-commerce AI or data-infrastructure research, but they do not study agents with sustained autonomy, delegated authority, planning, tool use, or market interaction.

| Work | Status | Theme | Why It Is Outside the Core |
|---|---|---|---|
| [SynthAVE: Scalable Synthetic Labeling for E-Commerce with LLM-Arena Validation](https://arxiv.org/abs/2607.07469) | arXiv 2026 | Product-attribute labeling and multi-LLM validation | The “arena” is a majority-vote ensemble of LLM judges, not interacting commercial agents. |
| [Learning Reasons for Product Returns on E-Commerce](https://aclanthology.org/2024.ecnlp-1.1/) | ECNLP 2024 | Product-return reason prediction | Predicts return reasons but does not perform return, refund, dispute, or recourse actions. |

## Curation Notes

- `AgenticPay` is retained in the core list as negotiation and evaluation work, not as a payment-clearing system.
- `Market-Bench` is retained as a multi-agent procurement, pricing, and market-outcome benchmark, not as a real delegated commerce deployment.
- `RecGPT-V3` is retained as production-scale agentic recommendation infrastructure, not as an autonomous transaction agent.
- `SynthAVE` remains outside the core because multiple LLM judges do not by themselves constitute a multi-agent commerce system.
- Agent-based market simulations and benchmarks should remain explicitly separated from real agents acting under delegated commercial authority.
