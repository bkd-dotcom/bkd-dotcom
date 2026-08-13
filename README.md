<div align="center">

# Binay Dalai

```
@@@@@@@@@@@@@@@%#%%%88%%8&#@@@@@@%%@@@@@@@@@@@@@@@
@@@@@@@@@@@@%@@%888&8%@@@#####888##%@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@%8&*&***&&+=+&***#@@@@%%%@@@@@@@@@@
@@@@@@@@@%%##%#&&*++;::::;*#8&&#%%%%#8#%%@@@@@@@@@
@@@@@@@@%%8&#%%8**+=;===&#%8+++**+*#%%@@@@@@@@@@@@
@@@@@@@%%88#@%%#8#&&8&8&&***++==+*#@@@@@@@@@@@@@@@
@@@@@@@%#8%@%#8#8##8+===;;+**==8%@@@@@@@@@@@@@@@@@
@@@@@@%88%%@%%8*=*##*++===++&#@@@@@@@@@@@%%%%@@@@@
@@@@%%#88#%%%8+=;+&+**&8&*+&%#8&*&&&#%@@%###%%@@@@
@@@@%%##8&8#8&*+;+&;,::-,..-:::;=+::=+*&8&8#%%@@@@
@@@@@%##8&&#8&&8&&&:.         -:;:--=*++&&8#%%@@@@
@@@@@%#88#%#88+==;:. ,.-=;,    .-,-;*8*++*&#%%@@@@
@@@@@@@%%%#8&*++=:. -;-;++;,.   ,-,*%+:=+*&#%%@@@@
@@@@@@%%%#8#&+=;==:-=:,.;*,.., .;:,*%+:=+*&#%@@@@@
@@@@@%%##888****&&**=+=+=;-;;. ,:,,&%*=+&8###%@@@@
@@@@@%%888&+;:-,--. ,=+*=:,;: ,;:-;8#++8%@@%%@@@@@
@@@@@@%#8&&*=;:,,-..=:-==;:-,-,=***##=&#%%@@@@@@@@
@@@@@@%%#8&*+=;:;=*&*+-,-,,.,:-=***#8*&##%%@@@@@@@
@@@@@@@%%##888&++8%@&*+;:-,,===+;*8#8*&8#%%@@@@@@@
@@@@@@@@@@@@@%&&8%@#88&*+;=+**&##8&*##888#%@@@@@@@
@@@@@@@@@@@@%8&#%@@%##888&88#%@@@#&*#@@%#%@@@@@@@@
@@@@@@@@@@@%#8#%@@@@@@@%%%@@@@@@@%#8#%@@@@@@@@@@@@
@@@@@@@@@@@%%%@@@@@@@@@@@@@@@@%@@@%8#%@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@%@@@%#%@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@%@@@@@@@@@@@@@@
```

**CS + Computational Math @ Penn State (Schreyer Honors)**
Application Developer Intern @IBM

[![Website](https://img.shields.io/badge/binaydalai.me-1A1712?style=flat-square&labelColor=1A1712&color=6E56CF)](https://binaydalai.me)
[![ORCID](https://img.shields.io/badge/Research-ORCID-6E56CF?style=flat-square)](https://orcid.org/0009-0009-6285-8305)
[![IEEE](https://img.shields.io/badge/IEEE-NMITCON%202025-6E56CF?style=flat-square)](https://ieeexplore.ieee.org/document/11188070)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-binay--dalai-6E56CF?style=flat-square)](https://www.linkedin.com/in/binay-dalai)

</div>

---

I mostly work on ML, optimization, and formal verification. Recently I've been building a
governance layer for AI coding agents: it figures out how much a given change should be
trusted and attaches a signed receipt so you can check the decision later.

### What I've built

| | Project | |
|---|---|---|
| **◆** | **[Signetry](https://github.com/Signetry)** | A change-control plane for coding agents. Any agent can open a PR; Signetry decides how much authority the change earned and signs the result with an Ed25519 receipt (in-toto / SLSA). It quarantines prompt-injection text on disk, runs an independent verifier, and does deterministic SAST across 7 languages. Ships as a kernel, a [GitHub Action](https://github.com/Signetry/action), a GitHub App, and editor plugins. |
| **◆** | **[Cauzon](https://github.com/bkd-dotcom/cauzon)** | Root-cause analysis for data incidents on DataHub. It walks the lineage upstream, finds the actual cause, and writes it back. |
| **◆** | **[TracePilot](https://github.com/bkd-dotcom/tracepilot)** | A multi-agent router that learns from its own Arize Phoenix traces and reroutes away from tools that keep failing. |
| **◆** | **[Transformer × QAOA](https://ieeexplore.ieee.org/document/11188070)** | IEEE NMITCON 2025 paper. A from-scratch PyTorch transformer with QAOA-optimized attention blocks. |
| **◆** | **5G-AKA verification** *(honors thesis, in progress)* | Formal verification of the 5G-AKA auth protocol with SAT/SMT (Z3), an NL-to-CNF pipeline, and a Tamarin baseline. |

### What I care about

Plenty of people are making AI agents more capable. I'm more interested in whether you can
trust what they do: keep the change inside a contract, have something the model can't
override check it, and be able to prove afterward what happened. Signetry is that idea built
out. The QAOA and 5G-AKA work comes from the same place, just applied to optimization and
protocols.

### Right now

- **@IBM** — generative AI on watsonx, and Watson services on OpenShift for clients.
- **Before that** — Lockheed Martin, reinforcement learning for threat assessment (85% success rate).
- **Tools I reach for** — PyTorch, Qiskit/QAOA, Z3/SMT, Coq/Rocq, and Python / C / Java / TypeScript.

---

<div align="center">
<sub>

[binaydalai.me](https://binaydalai.me) · [Research](https://binaydalai.me/research) · [Signetry](https://github.com/Signetry) · binaydalai2024@gmail.com

</sub>
</div>
