# Praison Ship steward (Claude `.claude/skills/steward` analog)

When watching a pull request:

1. Prefer **failing CI** → rerun workflows with `gh run rerun` before editing code.
2. Prefer **merge base** into the feature branch before large fixes.
3. Never **merge**, **approve**, or enable auto-merge — the human merges.
4. Run tests locally when changing workflow or ship modules.
5. Post a short PR comment when acknowledging review threads you cannot auto-resolve.