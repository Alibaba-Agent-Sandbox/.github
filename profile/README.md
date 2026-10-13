<div align="center">

**Agent Sandbox**

Cloud sandboxes for AI agents: create an isolated environment, run commands in it, and tear it down from the `abx` CLI or the Python and Node.js SDKs.

</div>

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

| Repository | English | 中文 |
|:--|:--|:--|
| CLI (`abx`) | [docs/en](https://github.com/alibaba-agent-sandbox/agent-sandbox/blob/main/docs/en/README.md) | [docs/zh](https://github.com/alibaba-agent-sandbox/agent-sandbox/blob/main/docs/zh/README.md) |
| Python SDK | [docs/en](https://github.com/alibaba-agent-sandbox/python-sdk/blob/main/docs/en/README.md) | [docs/zh](https://github.com/alibaba-agent-sandbox/python-sdk/blob/main/docs/zh/README.md) |
| Node.js SDK | [README](https://github.com/alibaba-agent-sandbox/nodejs-sdk/blob/main/README.md) | [README.zh-CN](https://github.com/alibaba-agent-sandbox/nodejs-sdk/blob/main/README.zh-CN.md) |
| Templates | [README](https://github.com/alibaba-agent-sandbox/awesome-templates/blob/main/README.md) | [README](https://github.com/alibaba-agent-sandbox/awesome-templates/blob/main/README.md) |
| Providers | [authoring](https://github.com/alibaba-agent-sandbox/awesome-providers/blob/main/docs/authoring.md) | [编写指南](https://github.com/alibaba-agent-sandbox/awesome-providers/blob/main/docs/authoring.zh-CN.md) |

Index pages: [CLI docs](https://github.com/alibaba-agent-sandbox/agent-sandbox/blob/main/docs/README.md), [Python SDK docs](https://github.com/alibaba-agent-sandbox/python-sdk/blob/main/docs/README.md).

## 中文

Agent Sandbox 是给 AI agent 用的云沙箱：用 `abx` 命令行，或 Python / Node.js SDK，创建隔离环境、在里面执行命令，然后销毁。

### 仓库

| 仓库 | 是什么 |
|:--|:--|
| [`agent-sandbox`](https://github.com/alibaba-agent-sandbox/agent-sandbox) | `abx` CLI（`npm install -g @agent-sandbox/cli`）。 |
| [`python-sdk`](https://github.com/alibaba-agent-sandbox/python-sdk) | Python 包 `agent-sandbox`（`agent_sandbox`）和 `agent-sandbox-server`（`agent_sandbox.server`）。 |
| [`nodejs-sdk`](https://github.com/alibaba-agent-sandbox/nodejs-sdk) | Node.js SDK（`@agent-sandbox/sdk`）。 |
| [`awesome-templates`](https://github.com/alibaba-agent-sandbox/awesome-templates) | 沙箱模板目录。 |
| [`awesome-providers`](https://github.com/alibaba-agent-sandbox/awesome-providers) | 可安装的沙箱 provider 插件。 |

### 安装

```bash
npm install -g @agent-sandbox/cli
pip install agent-sandbox
```

### 快速开始

```bash
npm install -g @agent-sandbox/cli
abx config init
abx create --template base
abx list
abx exec <sandbox-id> -- echo hello
```

文档链接见上面的表格。
