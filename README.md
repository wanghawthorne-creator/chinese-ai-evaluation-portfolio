[English](README.md) | [简体中文](README.zh-CN.md)

# Chinese AI Evaluation Portfolio

**Evaluating Search Intent, Cultural Context, and Information Quality in Chinese-Language AI Systems**

Independent AI Evaluation Research · Bilingual case-based portfolio · Assessment v1.0

## Project Overview

This portfolio examines how Chinese-language AI responses interpret user intent, handle cultural context, support factual claims, and communicate uncertainty. It uses approved, anonymized excerpts from authentic interactions alongside traceable external sources.

The collection contains **10 case units from 9 ordinary ChatGPT conversations**. CEA-007 and CEA-008 address different tasks in the same conversation. A separate web-result track evaluates **7 newly retrieved pages across CEA-020, CEA-021, and CEA-022**. These pages were retrieved on **11 November 2026**; they do not recreate historical search rankings.

This is an independent, AI-assisted research project. It is not commissioned work for, employment with, or an official assessment of RWS, TELUS Digital, Google, or another employer.

## Research Objectives

- Distinguish literal wording from pragmatic intent, including informal Chinese, community terminology, and implicit constraints.
- Evaluate cultural interpretation while avoiding stereotypes and unsupported generalizations.
- Separate verifiable facts, theoretical interpretations, hypotheses, and causal claims.
- Examine whether source scope, publication dates, and product versions support the conclusions being drawn.
- Make assessment judgments reviewable through explicit criteria, evidence, alternative explanations, and limitations.

## Evaluation Dimensions

The two tracks use separate criteria rather than treating answer quality and webpage relevance as the same task.

| Track A — AI Response Evaluation | Code |
|---|---|
| Intent Understanding | IU |
| Semantic Relevance | SR |
| Cultural Competence | CC |
| Factual Accuracy | FA |
| Temporal Relevance | TR |
| Source Credibility | SC |
| Response Helpfulness | RH |
| Uncertainty Calibration | UC |

Track B evaluates **query–result relevance (WR), authority and evidence fit (WA), temporal fit (WT), and cultural/contextual fit (WC)**. Claim accuracy is checked separately against the available evidence.

Applicable dimensions use project-specific **0–4 ordinal anchors**. **NA** means *not applicable*; **NE** means *not evaluable from the available evidence*. Neither is zero. There is no composite score, model accuracy rate, or cross-case league table. See the [evaluation rubric](methodology/evaluation-rubric.md).

## Research Methodology

1. Define the approved question–response segment and any included follow-ups.
2. Identify explicit constraints and defensible implicit intent.
3. Separate response claims, background assumptions, and reviewer-generated questions.
4. Check material claims against sources appropriate to the topic and historical time.
5. Record scores with supporting excerpts, alternative readings, improvement recommendations, and evidence gaps.

Only necessary anonymized excerpts are distributed. Private conversation archives and identifying provenance remain outside this repository. Missing images or historical citation mappings are recorded as research limitations, not automatically attributed to the AI as errors. The full approach is described in the [research framework](methodology/research-framework.md).

## Featured Evaluation Cases

| Case | Focus | Web-result evaluation |
|---|---|---|
| [CEA-028 — AI Nostalgia Images: From a Personal Feed to Social Causal Claims](cases/ai-response-evaluation/CEA-028.md) | Personal-feed observations, causal claims, and uncertainty | — |
| [CEA-022 — Measuring Rural Work: Operational Definitions and Teaching Scenarios](cases/ai-response-evaluation/CEA-022.md) | Rural work, operational definitions, and hypothetical examples | [Track B](cases/web-search-evaluation/CEA-022.md) |
| [CEA-021 — From a Weather Anomaly to Research on Social Trust](cases/ai-response-evaluation/CEA-021.md) | Risk communication, social trust, and research-summary precision | [Track B](cases/web-search-evaluation/CEA-021.md) |
| [CEA-020 — Grok Bot Group Chats: Product Facts, Popularity Inferences, and Versioned Multi-Agent Evidence](cases/ai-response-evaluation/CEA-020.md) | Product comparisons, meme explanations, and versioned evidence | [Track B](cases/web-search-evaluation/CEA-020.md) |
| [CEA-019 — The Simulation Argument: Three Alternatives, Consciousness Assumptions, and Game Analogies](cases/ai-response-evaluation/CEA-019.md) | Conditional argument, consciousness assumptions, and teaching analogies | — |
| [CEA-011 — “General CZ”: Context Clarification and the Limits of Nickname Evidence](cases/ai-response-evaluation/CEA-011.md) | Community nicknames, missing context, and clarification | — |
| [CEA-007 — Pragmatic Intent in “Artsy” Self-Presentation and Caption Constraints](cases/ai-response-evaluation/CEA-007.md) | Informal Chinese, self-presentation, and English style constraints | — |
| [CEA-008 — Does “Crying Bot” Mean a Submission Account or an Automated Program?](cases/ai-response-evaluation/CEA-008.md) | Social-account usage of bot, song metadata, and interpretation | — |
| [CEA-004 — Distinguishing Collective Forgetting from the Mandela Effect](cases/ai-response-evaluation/CEA-004.md) | Shared false memories, social forgetting, and public narratives | — |
| [CEA-001 — The “Chinese Dragon” Metaphor and the Limits of Cultural Generalization](cases/ai-response-evaluation/CEA-001.md) | Book-specific metaphor, structural explanations, and cultural boundaries | — |

Case IDs retain their original research identifiers. Gaps in numbering reflect the approved selection, not missing files. The three Track B files are companion analyses of the same case units, not three additional independent cases.

## Key Findings

- **Context changes meaning.** A plausible social-account reading of *bot* differs from the agent-product meaning; a missing nickname context calls for clarification rather than an invented origin.
- **Explanatory coherence is not sufficient evidence.** CEA-028 offers a well-organized account but turns a qualified personal observation into unmeasured population and causal claims. Its central factual claims remain NE, rather than being declared false.
- **Boundaries can be a response strength.** CEA-019 preserves assumptions in the simulation argument; CEA-001 distinguishes theoretical interpretation from empirical research; CEA-022 separates teaching scenarios and proposed methods from completed fieldwork.
- **Verification should be claim-specific.** CEA-021 has identifiable official and research sources, while its summary of the trust study compresses important distinctions between information dimensions, trust components, and models.
- **Version and attribution matter.** CEA-020 distinguishes older research summaries from later versions. Refuting a reviewer inference or testing a user premise is not evidence that the AI made that assertion.

Read the [key findings report](reports/key-findings.md) for the evidence boundaries behind these conclusions.

## Research Limitations

This is a purposively selected qualitative collection, not a representative benchmark. Assessments are AI-assisted first-pass judgments; there were no independent human blinded ratings, inter-rater reliability estimates, or controlled retests. The collection does not establish population-level model performance, user satisfaction, or causal effects.

Some original posts, images, book editions, historical product states, and citation mappings remain unavailable. Current webpages cannot automatically establish past functionality. A score of 4 applies only to a declared, checked scope: for example, CEA-008's FA score covers song metadata, and CEA-022's covers methodological facts and census timing, not verified fieldwork outcomes. See [limitations](methodology/limitations.md).

## Skills Demonstrated

- Chinese pragmatic and cultural-context analysis
- Search-intent disambiguation and multi-turn task analysis
- Claim-level source verification and temporal/version reasoning
- Evaluation-rubric design and evidence-based annotation
- Social-science operationalization and causal-boundary assessment
- Bilingual research documentation and privacy-conscious evidence selection

## Project Navigation

| Resource | Contents |
|---|---|
| [Research framework](methodology/research-framework.md) | Research questions, scope, evidence units, and procedure |
| [Evaluation rubric](methodology/evaluation-rubric.md) | Separate Track A and Track B anchors, including NA and NE |
| [Limitations](methodology/limitations.md) | Sampling, missing evidence, reviewer role, and interpretation boundaries |
| [AI-response cases](cases/ai-response-evaluation/) | Ten bilingual case dossiers |
| [Web-result cases](cases/web-search-evaluation/) | Three companion dossiers covering seven newly retrieved pages |
| [Anonymized data notes](data/public-anonymized/README.md) | Schema, scope, and reuse boundaries for the [structured records](data/public-anonymized/evaluations.json) |
| [Key findings](reports/key-findings.md) | Cross-case synthesis with case-level links |

No open-source license has been added. Third-party sources are cited and linked rather than redistributed in full.
