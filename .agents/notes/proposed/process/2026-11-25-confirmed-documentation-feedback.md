# Decision: Correct confirmed documentation feedback

Status: proposed

## Problem

The organization profile installs a different project’s PyPI package and mixes an unqualified CLI install with release-specific commands. The contribution tables repeat the obsolete client package name.

## Decision

Name agent-sandbox-client in the profile and both contribution tables. Use python -m pip with --pre for the preview client. Pin the published CLI quick start to 0.5.10 and link current source guidance separately. Describe the Node SDK as an application-service client. Add this repository’s engineering-record entry point.

## API Design

N/A — this decision does not involve API changes.

## Alternatives considered

Only changing the pip command would leave the repository table and contribution instructions inconsistent. Switching published-install examples to unreleased source commands would create a second broken quick start.

## Dependencies

Official npm/PyPI package metadata; the CLI release and current source documentation at https://github.com/Alibaba-Agent-Sandbox/agent-sandbox.

## Test Strategy

Check changed Markdown links, bilingual wording, seven-section note structure and git diff hygiene. Use existing owner documentation gates where available. Runtime, image, deployment and model behavior are unchanged, so this prose correction does not require new cloud resources.

## Acceptance criteria

The profile and English/Chinese contribution tables name the correct client distribution. CLI examples identify their installation source. Local links and record structure pass; required remote gates pass before merge.

## Evidence

[Local documentation verification](../../../evidence/verify/2026-11-25-confirmed-documentation-feedback.md).
