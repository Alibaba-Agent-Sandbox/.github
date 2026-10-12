<div align="center">

**Welcome to Easy Sandbox**

</div>

## Repositories

| Repository | Description |
|:--|:--|
| [`easy-sandbox`](https://github.com/Easy-Sandbox/easy-sandbox) | The `ebx` CLI. Create and manage sandboxes, providers, and templates. |
| [`python-sdk`](https://github.com/Easy-Sandbox/python-sdk) | Python client SDK (`easy-sandbox`) and the in-sandbox server (`easy-sandbox-server`). |
| [`awesome-templates`](https://github.com/Easy-Sandbox/awesome-templates) | Community sandbox templates. |

## Quick start

Install the CLI (Node.js 20 or newer):

```bash
npm install -g @easy-sandbox/cli
ebx --version
```

Or use the Python SDK:

```bash
pip install easy-sandbox
```

```python
from easy_sandbox import Sandbox

async with await Sandbox.create(template="base") as sandbox:
    result = await sandbox.commands.run("echo hello")
    print(result.stdout, result.exit_code)
```

Credentials go in `ebx config` or `E2B_API_KEY`. Do not commit them.
