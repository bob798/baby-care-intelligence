# Baby Care Intelligence

**Evidence-grounded infant care tracking, longitudinal insights, and responsible AI decision support.**

> 从记录到理解：面向婴儿照护的多维观察、可追溯证据与干预反馈。
>
> From tracking to understanding — a research-driven, safety-first infant care intelligence project.

## Overview / 项目定位

Baby Care Intelligence is an **early-stage open research and engineering project**, exploring how to transform fragmented infant care records into explainable, context-aware insights.

婴儿照护不能仅凭一次喂奶量、一张便便照片或一段哭闹时间做判断。项目计划综合喂养、睡眠、哭闹、排泄和成长趋势，在可靠证据和明确安全边界约束下提供辅助观察与信息整理。

**Status: Research & discovery / 需求探索阶段。** Currently this repository documents observations, hypotheses and planned architecture. It **does not** claim to have implemented a diagnostic AI, validated an analysis model, or demonstrated clinical outcomes.

## Problem / 为什么做

- **Fragmented tracking:** care events are often stored as isolated entries.
- **Lack of context:** single observations can be misinterpreted without growth and behavior trends.
- **Weak feedback loops:** care actions and subsequent outcomes are rarely linked systematically.
- **Safety and trust:** AI-generated health information needs evidence, uncertainty disclosure and escalation boundaries.

## Proposed capabilities / 计划中的能力

| Layer | Planned capability |
| --- | --- |
| Capture | Multi-child profiles; feeding, sleep, crying, diapers, stool, cleaning and care interventions |
| Context | Longitudinal timeline, per-child baseline and missing-data awareness |
| Insights | Multi-signal patterns and descriptive stool/head-shape observation aids |
| Evidence | Source-linked guidance, age applicability, conditions and uncertainty |
| Feedback | Document interventions, outcomes and follow-up observations |
| Safety | Risk flagging and referral to professional care; no automated diagnosis |

## Research workflow / 研究流程

**Observation → Hypothesis → Evidence review → Prototype → Evaluation → Feedback**

We explicitly separate **observed facts**, **caregiver hypotheses**, **published evidence** and **unvalidated product ideas**.

## Repository structure / 仓库结构

```text
docs/
  daily/        # Anonymized daily observations and discovery notes
  research/     # Literature reviews and evidence assessments (planned)
  product/      # Requirements and roadmap (planned)
  architecture/ # Engineering design (planned)
```

### Daily field notes
- [2026-10-08 · 夜间哭闹、奶瓣便与多维观察](docs/daily/2026-10-08.md)
- [2026-10-09 · 喂养、睡眠、排泄和行为发育观察](docs/daily/2026-10-09.md)

## Research themes / 研究方向

- Infant care event modeling and longitudinal data analysis
- Evidence-grounded and uncertainty-aware AI assistance
- Safety guardrails for high-stakes recommendations
- Multimodal observation, including stool and head-shape photos
- Human-in-the-loop decision support and intervention feedback

## Privacy, evidence & safety

- Public notes are anonymized and should not include identifiable infant information, medical documents, or personal photographs.
- Observed correlations **must not** be presented as causal medical findings.
- This repository is **not a medical device or a substitute for pediatric care**.
- For symptoms of illness or dehydration, seek advice from a qualified clinician.
- Medical source material is linked and summarized rather than copied wholesale.
- Technical methods, experiments and clinical claims remain subject to future validation.

## Contributing & license

Project at an early exploratory stage; contributions and research feedback are welcome via GitHub Issues when enabled. No open-source license has yet been selected; public visibility does not itself grant reuse rights.
