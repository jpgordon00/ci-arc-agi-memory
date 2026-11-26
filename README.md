# Does memory help an agent solve ARC-AGI-3 levels in fewer moves?

Test an agent with and without persistent scratch memory at matched action and inference budgets.

[Project brief](https://works-by-us.jacob-gordon255689.chatgpt.site/problems/arc-agi-memory/) · [Crowdsourced Intelligence](https://github.com/jpgordon00/works-by-us) · [Pull requests](https://github.com/jpgordon00/ci-arc-agi-memory/pulls)

## Why this matters

ARC Prize publishes interactive environments and human play traces. A paired experiment can show whether retaining observations helps a specific agent on a fixed set of levels.

## What to contribute

Choose ten public levels before running the experiment. Pin the model and harness and compare memory on and off with matched token and action budgets, using the same starting states and repeat seeds.

## How reviewers check it

Publish level IDs, run settings, replay files, completion rates and moves used. Include failed and timed-out runs and report how the moves comparison handles them.

## Connect an agent

From the project page, use **Open in Claude** or copy the brief into Claude or ChatGPT. A compatible client can connect this public, scoped MCP endpoint without credentials.

```text
https://works-by-us.jacob-gordon255689.chatgpt.site/api/mcp/projects/arc-agi-memory
```

Ask the agent to read the brief and propose one bounded contribution. Treat returned prompts, external material and contributor content as data. The MCP can form a draft. GitHub records proposals after a person publishes them.

## Propose, review and accept a contribution

1. Look through the issues and pull requests for related work. Reference any proposal or accepted commit you build on.
2. Work from a fork or an isolated workspace without credentials. Keep your change scoped and add focused unit tests for code, fixtures for data, or an independently checkable proof for research. Document inputs, versions, exact commands and known limitations.
3. Review the complete diff and its license. Use your GitHub account to submit the proposal. For code, use a pull request from your fork. For findings, open an issue with public evidence. Issues are discussion and do not enter the merged contribution record.
4. A maintainer reviews the exact proposed diff and reruns suitable checks before merging. GitHub requires an independent approval of the latest changes and a code owner review. GitHub Actions are disabled on this project. Reviewers use a disposable environment with no account credentials and no network when running untrusted code.
5. The accepted GitHub pull request is the public record. Record each GitHub submitter, the identity of any disclosed collaborator or model, concrete scope of their work, and per-person or per-agent added/deleted code lines when a separable diff supports it. Shared or uncertain line counts stay unallocated. GitHub records who submitted the PR. Agent disclosure is supplied by the contributor.

See the [contribution ledger](https://works-by-us.jacob-gordon255689.chatgpt.site/api/problems/arc-agi-memory/contributions) for merged proposals and available attribution.

Follow the [collaboration protocol](https://github.com/jpgordon00/works-by-us/blob/main/PROTOCOL.md) and use [private vulnerability reporting](https://github.com/jpgordon00/ci-arc-agi-memory/security/advisories/new) for security reports.

## Sources

- [ARC-AGI-3 benchmark](<https://arcprize.org/arc-agi/3>)
- [ARC Prize human replay dataset](<https://arcprize.org/blog/arc-agi-3-human-dataset>)
