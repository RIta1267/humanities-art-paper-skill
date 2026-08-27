---
name: humanities-art-paper
description: Humanities, social science, and arts paper writing workflow for Chinese and bilingual academic work. Use when Codex helps with arts, musicology, art theory, folklore, intangible cultural heritage, education, cultural studies, or related humanities/social-science papers, including topic refinement, research-question diagnosis, literature review, argument structure, fieldwork/archive/image/music evidence, CSSCI-style Chinese revision, abstracts, conclusions, thesis chapters, journal manuscripts, opening reports, and research figures or tables.
---

# Humanities Art Paper

## Overview

Use this skill to turn humanities, social-science, and arts research material into a defensible paper argument. Prefer interpretive rigor, historical context, textual/material analysis, and explicit evidence chains over STEM-style IMRaD defaults.

## Operating Principles

- Treat the paper as an argument, not a topic introduction.
- Preserve the user's disciplinary voice unless the user asks for heavy rewriting.
- Work top-down: fix the research question, claim, evidence, and section logic before polishing sentences.
- Separate what the material shows, what the author infers, and what existing scholarship claims.
- Avoid inflated theory, vague value claims, policy slogans, and unsupported "important significance" language.
- Do not invent citations, fieldwork details, archival sources, dates, places, page numbers, images, scores, interviews, or statistics.
- When evidence is missing, mark the gap and propose what kind of material would support the claim.

## Workflow

1. Identify the task: topic design, outline, literature review, section drafting, revision, abstract/conclusion, peer-review response, translation, or figure/table design.
2. Identify the genre: course paper, thesis/dissertation chapter, journal article, CSSCI-style manuscript, opening report, project proposal, conference paper, or presentation.
3. Identify the field and materials: musicology, art theory, art education, folklore, ICH, cultural studies, theatre/opera, dance, visual art, media, museum studies, or another stated field.
4. Diagnose the research spine: research object, core question, key concepts, material basis, method, argument, contribution, and limits.
5. Check section hierarchy before drafting: introduction, materials/method, analysis sections, discussion, and conclusion must not be flattened into one undifferentiated list.
6. Decide whether tables, figures, captions, or legends are needed to make the material basis and argument visible.
7. Produce the requested output with explicit assumptions and evidence gaps.

If the user provides only a broad topic, first return a compact diagnosis with 2-4 possible research questions and the evidence each would require. If the user provides draft text, revise or critique the text directly before proposing a new structure.

## Stage Gates

Use a gated workflow for substantial paper tasks. Do not draft past a failed gate unless the user explicitly asks for a quick sketch.

1. Intake gate: confirm genre, discipline, target audience, available materials, and output needed now.
2. Question gate: produce one sentence in this form: "This paper explains [object/change/tension] through [materials/method], arguing that [claim] within [scope/boundary]." If this sentence cannot be written, narrow the topic before drafting.
3. Terms gate: create a short terminology ledger for recurring concepts, place names, repertoire names, institutions, translations, and abbreviations.
4. Evidence gate: map each major claim to available or missing evidence.
5. Structure gate: create section blueprints and verify that same-level sections are truly parallel before writing full prose.
6. Visual evidence gate: decide which claims need tables, figures, captions, or legends; skip visuals that only decorate or repeat prose.
7. Draft gate: draft or revise one section at a time, keeping each paragraph to one job.
8. Review gate: run layered critique or reviewer-style adversarial checks when the user asks for review, defense preparation, or submission readiness.
9. Integrity gate: check for fabricated sources, unsupported claims, concept drift, overbroad contribution, and mismatch between evidence and claim.
10. Delivery gate: return the requested artifact plus a short "ready / needs author check / blocked" status.

For the detailed humanistic version of these gates, read `references/workflow-gates.md`.

## Task Routing

- For staged end-to-end paper work, read `references/workflow-gates.md` first, then load only the needed task reference.
- For topic, title, outline, opening report, chapter arrangement, or argument diagnosis, read `references/paper-architecture.md`.
- For literature review, citation positioning, research history, and avoiding author-by-author summaries, read `references/literature-review.md`.
- For fieldwork, interview, archive, image, score, policy, local gazetteer, catalog, repertoire, or historical evidence, read `references/evidence-materials.md`.
- For Chinese academic prose, CSSCI-style revision, abstracts, keywords, conclusions, and section transitions, read `references/style-revision.md`.
- For tables, conceptual diagrams, transmission maps, genealogies, timelines, musical/formal analysis charts, and humanities-friendly figures, read `references/figures-tables.md`.

## Output Standards

When generating or revising paper content:

- Make the central claim visible.
- Connect every major claim to a material type or scholarly debate.
- Prefer concrete chapter titles over decorative or slogan-like titles.
- Keep first-level headings at consistent argumentative rank: do not place a materials/method section, three analytical dimensions, a scope discussion, and the conclusion as if all were equivalent analytical sections.
- Use tables and figures to expose source scope, coding logic, comparison, chronology, spatial relations, or analytical mechanisms; do not add them as decorative academic furniture.
- Every proposed table or figure must have an in-text function, a source note, and a caption or legend that explains categories, symbols, abbreviations, and evidence limits.
- Keep theory as an analytical tool, not a name-dropping layer.
- Assign each paragraph one primary job: context, problem, literature position, method/material, analysis, comparison, implication, or limitation.
- For Chinese outputs, use clear academic Chinese with controlled abstraction.
- For English outputs, preserve humanities-style nuance and avoid flattening concepts into generic social-science phrasing.

## Common Deliverables

- Research-question diagnosis: object, question, hypothesis/claim, evidence, method, risk.
- Paper outline: title, abstract skeleton, chapter structure, section claims, evidence placement.
- Literature review map: schools, debates, methods, missing questions, position of this paper.
- Draft revision: argument-level notes first, then paragraph-level rewrites.
- Four-layer critique: foundation, structure, paragraph function, sentence style.
- Reviewer simulation: likely reviewer objections, evidence vulnerabilities, concept attacks, and revision priorities.
- Revision dossier: response-to-reviewer plan, change log, unresolved author checks.
- Figure/table plan: figure type, required data/materials, table fields, caption/legend logic, in-text placement, source notes, and permission risks.
- Submission polish: title, abstract, keywords, introduction, conclusion, and response-to-reviewer text.

## Clarifying Questions

Ask only what is needed. Useful questions include:

- What is the target genre and length?
- What is the discipline or journal/thesis context?
- What materials are already available?
- Is the priority novelty, structure, literature review, language polish, or submission readiness?
