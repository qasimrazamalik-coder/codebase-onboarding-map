# Contract

## Capability
Build a compact onboarding map from an authorized repository inventory, highlighting entry points and ownership gaps.

## Input root
`items` with fields: id, source, target, kind.

## Output
JSON containing `skill` and deterministic findings, ranking, mapping, plan or redaction results.

Reject malformed JSON. Do not infer authorization or fabricate evidence.
