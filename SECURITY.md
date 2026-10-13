# Security Policy

## Supported Versions

Agent Sandbox is unreleased. The `main` branch of each repository in this organization is the supported line.

| Version | Supported          |
|---------|--------------------|
| `main`  | :white_check_mark: |

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

Report them privately by email:

📧 **liuyu@xmail.tech**

You can also open a private GitHub Security Advisory on the repository that contains the code:

- CLI (`abx`, `@agent-sandbox/cli`): https://github.com/alibaba-agent-sandbox/agent-sandbox/security/advisories/new
- Python SDK (`agent-sandbox`, `agent-sandbox-server`): https://github.com/alibaba-agent-sandbox/python-sdk/security/advisories/new
- Node.js SDK (`@agent-sandbox/sdk`): https://github.com/alibaba-agent-sandbox/nodejs-sdk/security/advisories/new
- Templates: https://github.com/alibaba-agent-sandbox/awesome-templates/security/advisories/new
- Providers: https://github.com/alibaba-agent-sandbox/awesome-providers/security/advisories/new

### What to Include

- A description of the vulnerability
- Steps to reproduce the issue
- Potential impact
- Any suggested fix (if applicable)

Do not send live API keys, access keys, or a copy of `~/.abx/.env`.

### Response Timeline

| Action | Timeframe |
|--------|-----------|
| Acknowledgment of report | Within **48 hours** |
| Initial assessment | Within **5 business days** |
| Fix development & testing | Within **30 days** (critical), **90 days** (non-critical) |
| Public disclosure | After a fix is released |

### Process

1. You report the vulnerability via email or a GitHub Security Advisory
2. We acknowledge receipt and begin investigation
3. We work with you to understand and validate the issue
4. We develop and test a fix
5. We release the fix and publish a security advisory
6. We credit you in the advisory (unless you prefer anonymity)

## Security Best Practices for Users

- Keep `@agent-sandbox/cli`, `agent-sandbox`, and `@agent-sandbox/sdk` updated
- Never commit API keys, tokens, or credentials
- Use `abx config` or `ABX_*` environment variables for credentials
- Review a sandbox template and a provider manifest before you install it

## Scope

This policy covers every repository in the `alibaba-agent-sandbox` organization: the `abx` CLI, the Python SDK and in-sandbox server, the Node.js SDK, template catalog, and provider plugins.

Thank you for helping keep Agent Sandbox and its users safe.
