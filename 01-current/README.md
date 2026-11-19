# NOX

**A Safety-Critical Containment Architecture for Hostile Agentic Artificial Intelligence**

NOX is an independent research program focused on safety-critical containment architecture for hostile or potentially hostile agentic artificial intelligence.

## Current baseline

The only current architecture baseline in this repository is:

**NOX: A Safety-Critical Containment Architecture for Hostile Agentic Artificial Intelligence — Consolidated Architecture and Assurance Baseline, Candidate Version 1.0**

- [Stable PDF reading copy](01-current/NOX_Consolidated_Architecture_and_Assurance_Baseline_Candidate_v1.0.pdf)
- [Editable DOCX source](01-current/NOX_Consolidated_Architecture_and_Assurance_Baseline_Candidate_v1.0.docx)
- [Current-baseline status and authority](01-current/README.md)

## Status

Candidate engineering requirements baseline.

The current manuscript specifies and architecturally allocates the NOX containment requirements. It does **not** establish that NOX has been physically implemented, completely formally verified, independently validated, certified, or authorized for hostile-agent execution.

## Governing rule

NOX contains only what is required and explicitly authorized. Unnecessary elements are removed. Any element that cannot be removed remains inside the evaluated boundary, is treated as hostile, and must be demonstrated causally isolated within the defined system model and authorization envelope. Residual uncertainty capable of invalidating a required safety property blocks authorization.

## Repository structure

- `01-current/` contains the single current baseline.
- `99-archive/` is reserved for superseded material retained only for provenance.
- `CITATION.cff` contains citation metadata.
- `CHANGELOG.md` records controlled public changes.
- `SECURITY.md` defines private reporting expectations.
- `LICENSE` defines reuse under Creative Commons Attribution 4.0 International (`CC-BY-4.0`).

## Historical material

Earlier NOX documents are historical and non-normative unless their requirements were explicitly re-derived and incorporated into Candidate v1.0. Historical material must not be placed in `01-current/`.

## Author

Donald Heese  
Independent Researcher

## Citation

Use the repository's **Cite this repository** function after `CITATION.cff` is committed. Add the DOI to `CITATION.cff` after an archived release receives one.

