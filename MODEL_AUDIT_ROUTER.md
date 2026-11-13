# Independent Model Audit Router — Google-Colab-Programs

**Revision date:** 2026-11-13

## Data integrity and evidence rules
- Never replace real or maintainer-provided data with invented, generated, synthetic or placeholder records.
- Trace sources, licences, collection dates, previous Git revisions and limitations before changing a dataset.
- If source evidence is unavailable, preserve the existing data and mark it unknown/unverified. Never invent a replacement.
- Keep synthetic data in clearly labelled, isolated tests/examples only.
- Do not fabricate real people, official records, source links, metrics, customers, partnerships, deployments or endorsements.
- Test claims require reproducible results on the exact commit being reviewed.

## README preservation
Recover the last maintainer-authored README from Git history and preserve it intact. Do not rewrite or replace it. Append AI-generated notes only as a dated, clearly labelled secondary section at the very bottom.

## Independent audit roles
1. Data provenance and real-vs-synthetic checker.
2. Architecture and implementation reviewer.
3. Security, privacy and dependency reviewer.
4. Test, CI, build and reproducibility reviewer.
5. README history, licensing, attribution and links reviewer.
6. Public claims and career/research evidence reviewer.

## Audit steps
1. Record repository URL, default branch, exact HEAD SHA and fork/original status.
2. Classify work as merged, open, closed-unmerged, reverted or unverified.
3. Inventory runtime data, fixtures, generated artefacts, APIs and provenance.
4. Compare README with its pre-AI Git-history baseline.
5. Run exact install/build/lint/test commands; inspect CI for suppressed failures.
6. Review security, privacy, accessibility, error handling, edge cases and performance.
7. Verify links and public-facing claims.
8. Publish evidence before changing code or data.

## Finding format
Severity (**P0/P1/P2/P3**), exact path/line, reproduction, expected vs actual, evidence and SHA, confirmed/suspected/unverifiable status, minimal fix, regression test, and data/README impact.

## Merge gate
- [ ] No fabricated data presented as real or official.
- [ ] Original/user-provided data preserved without silent substitutions.
- [ ] Synthetic examples labelled and isolated.
- [ ] Original README preserved; AI notes at bottom only.
- [ ] Exact-head tests/CI checked; failures disclosed.
- [ ] No secrets, private personal details, classified or confidential information.
- [ ] Licensing and attribution retained.
- [ ] Second independent review and maintainer approval completed.

Repository: **Google-Colab-Programs**. Do not infer functionality from repository name or roadmap. Do not merge, delete, force-push, overwrite datasets or alter the original README during an audit. The repository owner has final approval.
