# Agent Sandbox

Agent Sandbox is a cloud sandbox for AI agents: create an isolated environment, run commands in it, and tear it down from the `abx` CLI or the Python and Node.js SDKs.

GitHub renders [`profile/README.md`](profile/README.md) as the organization landing page. This file is the repository README.

## Repositories

| Repository | What it is |
|:--|:--|
| [`agent-sandbox`](https://github.com/alibaba-agent-sandbox/agent-sandbox) | The `abx` CLI (`npm install -g @agent-sandbox/cli`). |
| [`python-sdk`](https://github.com/alibaba-agent-sandbox/python-sdk) | Python packages `agent-sandbox` (`agent_sandbox`) and `agent-sandbox-server` (`agent_sandbox.server`). |
| [`nodejs-sdk`](https://github.com/alibaba-agent-sandbox/nodejs-sdk) | Node.js SDK (`@agent-sandbox/sdk`). |
| [`awesome-templates`](https://github.com/alibaba-agent-sandbox/awesome-templates) | Sandbox template catalog. |
| [`awesome-providers`](https://github.com/alibaba-agent-sandbox/awesome-providers) | Installable sandbox provider plugins. |

## Install

```bash
npm install -g @agent-sandbox/cli
pip install agent-sandbox
```

## Quick start

```bash
npm install -g @agent-sandbox/cli
abx config init
abx create --template base
abx list
abx exec <sandbox-id> -- echo hello
```

## Docs

| Repository | Docs |
|:--|:--|
| CLI (`abx`) | [docs/en](https://github.com/alibaba-agent-sandbox/agent-sandbox/blob/main/docs/en/README.md) |
| Python SDK | [docs/en](https://github.com/alibaba-agent-sandbox/python-sdk/blob/main/docs/en/README.md) |
| Node.js SDK | [README](https://github.com/alibaba-agent-sandbox/nodejs-sdk/blob/main/README.md) |
| Templates | [README](https://github.com/alibaba-agent-sandbox/awesome-templates/blob/main/README.md) |
| Providers | [authoring](https://github.com/alibaba-agent-sandbox/awesome-providers/blob/main/docs/authoring.md) |

Index pages: [CLI docs](https://github.com/alibaba-agent-sandbox/agent-sandbox/blob/main/docs/README.md), [Python SDK docs](https://github.com/alibaba-agent-sandbox/python-sdk/blob/main/docs/README.md).
