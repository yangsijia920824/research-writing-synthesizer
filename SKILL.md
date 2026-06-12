---
name: research-writing-synthesizer
description: Build a provenance-preserving research writing corpus from selected papers, label and reorganize evidence into a contribution-centered manuscript outline, and synthesize original evidence-grounded prose through comparison, induction, and structural rewriting. Use when Codex needs to draft or improve a research introduction, literature-based argument, grant background, or other scholarly section; convert a paper collection into reusable writing evidence; infer an outline from how strong papers organize their arguments; combine expressions without copying; preserve sentence-level source traceability; or audit a draft for logic, citation support, overlap, and alignment with the study's core contribution.
---

# Research Writing Synthesizer

## Overview

Turn a focused set of papers into a traceable evidence-and-expression corpus, derive the manuscript's logic from recurring writing purposes, and synthesize prose that fits the user's actual study. Treat published text as evidence and examples, not as a template to copy.

## Operating Principles

- Work backward from the manuscript's core contribution and intended claim.
- Organize sources by writing purpose rather than reading every paper sequentially.
- Preserve provenance from extraction through the final draft.
- Keep a complete source map and a separate working copy.
- Infer structure from the selected corpus; do not impose a universal introduction formula.
- Distinguish linguistic support from factual support. Verify every factual claim and citation.
- Prefer a small number of highly relevant examples over an indiscriminate phrase bank.
- Never let fluent synthesis conceal unsupported logic or evidence.

## Choose the Workflow

Use the full workflow when the user supplies papers or a literature library and wants a section built from the ground up:

1. Define the writing target.
2. Select the focused corpus.
3. Build the source document.
4. Label writing purposes.
5. Derive and populate the outline.
6. Synthesize sentences.
7. Audit evidence, originality, and logic.

Use a partial workflow when the user already has:

- a source corpus: begin with labeling;
- labeled evidence: begin with outline derivation;
- an outline and evidence: begin with sentence synthesis;
- a draft: perform the provenance and quality audit first, then repair weak passages.

## Step 1: Define the Writing Target

Before collecting text, state:

- section and document type;
- target audience or journal;
- study's core contribution;
- question the section must answer;
- claims that require evidence;
- known results and what remains uncertain.

If results are not yet stable, build the background and gap logic but leave the detailed "this work" paragraph provisional. Do not invent outcomes.

## Step 2: Select the Focused Corpus

Choose approximately 10-30 highly relevant papers unless the user's task requires a different scope. Favor papers that directly address the contribution, problem, method, material, model, or application criterion.

Record why each paper was selected. Include strategically different examples when they reveal alternative argument structures or terminology.

Read [references/source-corpus-pipeline.md](references/source-corpus-pipeline.md) before extracting source text.

## Step 3: Build and Label the Source Corpus

Extract each relevant introduction or section completely enough to establish its boundaries. Preserve the citation, article boundary, section title, and source order.

Assign concise purpose labels such as:

```text
[clinical burden]
[current diagnostic limitation]
[desired capability]
[prior solution]
[remaining gap]
[why the gap matters]
[this study]
```

Labels describe what the passage does in the argument, not merely what its words mean. Group tightly connected sentences under one label. Label target-relevant material more finely and peripheral material more coarsely.

Read [references/labeling-and-outline.md](references/labeling-and-outline.md) for granularity rules and integrity checks.

## Step 4: Derive the Outline

Create three logical views:

- **Complete map:** immutable copy of all labeled source passages.
- **Working queue:** duplicate used for sorting evidence.
- **Outline workspace:** headings representing candidate writing points.

Scan label sequences across papers and infer recurring argument moves. Create headings only when they serve the user's contribution. Cut relevant units from the working queue into the outline workspace so the residual queue visibly shrinks. Never cut from the complete map.

Allow repeated cycles such as problem -> solution -> new problem. Explain why a gap matters; "few studies exist" is not sufficient justification.

Keep competing outlines when the corpus supports more than one defensible narrative. Select among them based on the user's contribution, evidence strength, audience, and section length.

## Step 5: Synthesize Original Sentences

For each intended sentence:

1. Specify its semantic elements, for example `A + B + C`.
2. Find examples serving the same writing purpose.
3. Compare candidates and retain the strongest one to three structures.
4. If no example contains all elements, combine compatible elements from several examples.
5. Separate grammatical skeleton from content-bearing words and phrases.
6. Rebuild the sentence around the user's facts, terminology, and causal logic.
7. Compare it against the remaining examples and improve clarity and precision.
8. Verify every factual claim and attach the correct citation.

Use temporary alternatives separated by `/` when useful, but resolve them before delivery.

Read [references/sentence-synthesis.md](references/sentence-synthesis.md) before drafting substantial prose.

## Step 6: Audit and Deliver

Read [references/provenance-and-quality-control.md](references/provenance-and-quality-control.md), then verify:

- all important writing points support the core contribution;
- claims follow a valid logical sequence;
- gap statements explain significance;
- factual content is supported by checked sources;
- citations point to sources actually establishing the claim;
- borrowed wording has been structurally rewritten;
- adjacent sentences do not repeat the same function;
- transitions reflect real logical relations;
- no labeled evidence was silently lost or duplicated;
- uncertainty and conflicting evidence remain visible.

Deliver the result with:

1. the proposed outline or argument map;
2. the synthesized draft;
3. claim-to-source notes or another traceable provenance form;
4. unresolved evidence gaps and verification needs;
5. alternative wording or structure only where it changes a meaningful choice.

## Guardrails

- Do not fabricate papers, citations, data, results, or consensus.
- Do not cite a secondary reference without checking that it supports the claim.
- Do not copy long passages or disguise copying through superficial synonym replacement.
- Do not treat fixed overlap percentages as universal legal or journal standards.
- Do not use a transition word unless the underlying relationship warrants it.
- Do not force every corpus item into the final manuscript.
- Do not equate absence in a limited search with a genuine research gap.
- Do not finalize the study-specific closing paragraph before the study's actual findings are known.
