# Engineering records: organization profile

This repository owns the organization profile and shared contribution instructions.
New records use English. A change includes a decision note and dated verification.

- Notes: `notes/{proposed,implemented}/<architecture|feature|process>/YYYY-MM-DD-<slug>.md`.
- Rejected and superseded decisions use flat state directories; `Status:` matches the directory.
- Verification: `evidence/verify/YYYY-MM-DD-<slug>.md`, with exact scope, commands, results and limitations.
- Use Problem, Decision, API Design, Alternatives considered, Dependencies, Test Strategy and Acceptance criteria sections.
- Preserve merged evidence. Local documentation checks do not establish product, package or cloud acceptance.
- Include scoped records in the repository PR; require current-head CI/review and verify the actual merge.
- Keep credentials and private data out of records. Cross-repository links use absolute GitHub URLs.

- [Confirmed documentation feedback](notes/proposed/process/2026-11-25-confirmed-documentation-feedback.md) · [verification](evidence/verify/2026-11-25-confirmed-documentation-feedback.md).
