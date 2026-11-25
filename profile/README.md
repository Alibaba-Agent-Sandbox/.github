<div align="center">

**Agent Sandbox**

Cloud sandboxes for AI agents: create an isolated environment, run commands in it, and tear it down from the `abx` CLI or the Python SDK. The Node.js SDK connects to application services in running sandboxes.

</div>

## Repositories

| Repository | What it is |
|:--|:--|
| [`agent-sandbox`](https://github.com/alibaba-agent-sandbox/agent-sandbox) | The `abx` CLI (`npm install -g @agent-sandbox/cli`). |
| [`python-sdk`](https://github.com/alibaba-agent-sandbox/python-sdk) | Python packages `agent-sandbox-client` (`agent_sandbox`) and `agent-sandbox-server` (`agent_sandbox.server`). |
| [`nodejs-sdk`](https://github.com/alibaba-agent-sandbox/nodejs-sdk) | Node.js SDK (`@agent-sandbox/sdk`). |
| [`awesome-templates`](https://github.com/alibaba-agent-sandbox/awesome-templates) | Sandbox template catalog. |
| [`awesome-providers`](https://github.com/alibaba-agent-sandbox/awesome-providers) | Installable sandbox provider plugins. |
| [`blogs`](https://github.com/alibaba-agent-sandbox/blogs) | Product notes and release write-ups. |

## Sites

| Site | URL |
|:--|:--|
| Official site | https://www.agent-sandbox.cn |
| Template and provider registry | https://registry.agent-sandbox.cn |

## Install

```bash
npm install -g @agent-sandbox/cli@0.5.10
python -m pip install --pre agent-sandbox-client
```

## Quick start

This example uses the published CLI 0.5.10. For the current source commands, see the [CLI guide](https://github.com/Alibaba-Agent-Sandbox/agent-sandbox/blob/main/docs/en/guide/getting-started.md).

```bash
npm install -g @agent-sandbox/cli@0.5.10
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
| Blog | [README](https://github.com/alibaba-agent-sandbox/blogs/blob/main/README.md) |

Index pages: [CLI docs](https://github.com/alibaba-agent-sandbox/agent-sandbox/blob/main/docs/README.md), [Python SDK docs](https://github.com/alibaba-agent-sandbox/python-sdk/blob/main/docs/README.md).
