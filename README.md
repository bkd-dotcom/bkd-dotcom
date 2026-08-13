<div align="center">

# Binay Dalai

```
@@@@@@@@@@@@@@@@@@@#@###%XXX88XX8%##@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@###%##%%Oo+~=~--;;-~~*xOXXO88%%%##@@@@@@@@@@@
@@@@@@@@@##8XX%O*=---";;"~"',:,;,::;==*+*oOX%#@@@@@@@@@@
@@@@@@@@@#XOO*~~~=~-":::,':;:";",:";,,;;~=*O8%##@@@@@@@@
@@@@@@@#%8xx+"=+-*o~-~:`',;:"''"~-*+":';-"~o888%#@@@@@@@
@@@@@@#%Xx==~";,'';:-;;""*~`.';-*~o+":',"=-=XXXX8%#@@@@@
@@@@@#%%x+---"",:::::";=*o+;',+++~:""";::~~"=xooOX%##@@@
@@@@#%O+;""-~":"+~==-;',:;:+"+=+-:";"::;,;~+=*+XX8%%##@@
@@#%8XO;',;;-"::";;"~~-;`;xx=~:.;o-~"~~:,:;;,"~=X88%%#@@
@#%8Xx;`:"+~;'`:":'`':*XX8XXXX-:,":',";:,:,',',~oxOOX8#@
#%XO+=+~==;,,'-Xo=+==O8O88X8X88o";~~~:;,``.',,,:~=~~+x8#
#8x*-;"=="",`;%%*X*=*xX%#%XXOOOxX*--~~+-...`.`;":~""~*X%
#%O*~:"~:'`.'X%%o*=oX####%%%%%%88OOO++++-' ..`'`:"=~~*O8
##8xx~`''`..+#%*+x~---~+oxXXXXX8Xo**+o++=~'...`.,+xOOOX%
###%%X`.,`..X%~~~;;-:'```;+o*o;,````','';=; ....+88%XXX8
%88XX+``;,':xo-;,;::',,',;~O="`,`':"~;',,=+`,.,:oOX8XXX8
XOo*="'';::"8x=++;;;:',:;~X#8x;;::--~~~":+.,~.`~O%%%8OxO
8O*=-;:8=';=O%+=;";;;;;-=8##8x*---"~~~+**-.=-..+8%#%%XOO
#%8O*~+@8o%Oo8X=~~--~===8X%#%Oxx+oxooooO8+:-*`.+X8%88xoO
@@#%Xx~o8Xo*=x%X*xx*~:"XXxOXO*oO+=oxxooo*-"';;"+xxxo**oX
@@#%Xx*XXxx*"+xOOx+-;oX'`';-;',::*X%%%O+-:,:-:;~=====*x8
##8Xx*+=o*~,,=**=-"=OXXO+=-'....`"Ooxxo=;,;;-"=++=--~+O%
##%Xx+~--;,'`-+oxoxOX8Xxoo+O+;,',`OXOo~",-~"=xxxo*~-=x8#
@#%O*~-;:'``.,~+X%X*~-:;=*==--;'.,*8%X-;`..`+xOOxo+=o8#@
@@#8x=:'``..`**-*oO+O8Xo+*xxO*==*~O8#*;,'```"*xOxo+*X%#@
@@@#%x-:'```"8o""-+oOxo+~;,'',,-=oxx+"""";;,"+xOOOOX8#@@
@@@@#8o~;,'`oXo;;;"=xOXX8XOOOOXOo*~-";-****~~+xX8%###@@@
@@@@@#8x+-:;Oxo::;;"-+*xxOxOOOx*=;"-;';*oo*+~+O8##@@@@@@
@@@@@@#8O*x8xxx",;;"""-~=====~";"~~;'',+*+=~~+O%#@@@@@@@
@@@@@@@#%%#OOxxx:,,:;"-""~===~=~~;::,'~~~--~*O8#@@@@@@@@
@@@@@@@@@@#%%8XXo::,,,:::"---";;;";:;:=O+=+oX%#@@@@@@@@@
@@@@@@@@@@@@##%%%O~-"--"--"-"---"""--"O%%%###@@@@@@@@@@@
@@@@@@@@@@@@@@@###8xo*****=-:""-~++**O##@@@@@@@@@@@@@@@@
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
