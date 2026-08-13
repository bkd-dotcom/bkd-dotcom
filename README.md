<div align="center">

# Binay Dalai

**CS + Computational Mathematics · Schreyer Honors, Penn State**
Application Developer Intern **@IBM**

*I build systems that learn — and systems you can prove.*

[![Website](https://img.shields.io/badge/binaydalai.me-1A1712?style=flat-square&labelColor=1A1712&color=6E56CF)](https://binaydalai.me)
[![Research](https://img.shields.io/badge/Research-ORCID-6E56CF?style=flat-square)](https://orcid.org/0009-0009-6285-8305)
[![IEEE](https://img.shields.io/badge/IEEE-NMITCON%202025-6E56CF?style=flat-square)](https://ieeexplore.ieee.org/document/11188070)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-binay--dalai-6E56CF?style=flat-square)](https://www.linkedin.com/in/binay-dalai)

</div>

---

My work lives where **machine learning, optimization, and formal methods** meet: teaching
systems to reason, then holding them to a standard they can't fake. Lately that's meant a
governance layer that decides how much authority an AI coding agent's change *earned* — and
seals the verdict in a signed receipt.

```
learn ──▶ optimize ──▶ verify ──▶ prove
  ML          QAOA         SAT/SMT      signed receipts
```

### Selected work

| | Project | What it is |
|---|---|---|
| **◆** | **[Signetry](https://github.com/Signetry)** | A change-control plane for coding agents. Any agent may *propose*; only Signetry decides how much authority a change earned and seals it in an **Ed25519 receipt** (in-toto / SLSA). On-disk prompt-injection quarantine, an independent verifier, deterministic 7-language SAST. Shipped as a governance kernel, a **[GitHub Action](https://github.com/Signetry/action)**, a GitHub App, and editor plugins. |
| **◆** | **[Cauzon](https://github.com/bkd-dotcom/cauzon)** | Path-grounded root-cause analysis for data incidents on DataHub — walks lineage upstream, *proves* the cause, writes it back. |
| **◆** | **[TracePilot](https://github.com/bkd-dotcom/tracepilot)** | A self-optimizing multi-agent router that learns from its own Arize Phoenix traces; an economic-memory auditor reroutes away from failing tools. |
| **◆** | **[Transformer × QAOA](https://ieeexplore.ieee.org/document/11188070)** | IEEE NMITCON 2025 — *Quantum-Assisted Optimization for Transformer Architectures.* A from-scratch PyTorch transformer with QAOA-optimized attention blocks. |
| **◆** | **5G-AKA verification** *(honors thesis, in progress)* | Formal verification of the 5G-AKA authentication protocol with SAT/SMT (Z3), an NL-to-CNF translation pipeline, and a Tamarin prover baseline. |

### The throughline

Most of the field is racing to make agents **more capable**. I'm interested in the harder,
quieter half of the problem: making their output **accountable** — bounded by a contract,
checked by something the model can't overrule, and provable after the fact. Signetry is that
idea shipped; the QAOA and 5G-AKA work is the same instinct in optimization and protocols.

### Currently

- **@IBM** — generative AI on watsonx; Watson services on OpenShift for enterprise clients.
- **Prior** — Lockheed Martin: reinforcement learning for threat assessment (85% success rate).
- **Working with** — PyTorch · Qiskit / QAOA · Z3 / SMT · Coq/Rocq · Python · C · Java · TypeScript

---

<div align="center">
<sub>

[binaydalai.me](https://binaydalai.me) · [Research](https://binaydalai.me/research) · [Signetry](https://github.com/Signetry) · binaydalai2024@gmail.com

*Proof over promises.*

</sub>
</div>
