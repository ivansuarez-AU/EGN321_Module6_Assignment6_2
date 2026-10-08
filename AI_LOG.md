# AI_LOG.md

Tool: Ollama
Model: qwen2.5:0.5b

## Purpose
Use a local small language model to review deterministic comparison evidence,
challenge conclusions, propose testable hypotheses, and help draft the report.

## Deterministic evidence
Comparable points: 1747
Mean signed difference: 1.735 degrees C
Mean absolute difference: 1.735 degrees C
Maximum absolute difference: 2.603 degrees C

Status counts:
{'OK': 1747, 'MISSING': 33, 'REJECTED': 14, 'SUSPICIOUS': 6}

## AI tasks performed
1. Proposed hypotheses from supplied evidence.
2. Red-teamed a provisional conclusion.
3. Drafted a report using the supplied evidence and review notes.

## Verification rule
AI output is not treated as evidence.
Claims must be verified against Python results, plots, source data, or a new deterministic test.

## Instructor/student review
Document here:
- Which AI suggestions were accepted?
- Which were rejected?
- What deterministic test was added?
- What changed in the final report?
