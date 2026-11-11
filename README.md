# unslop

An agent skill that cuts AI tells from writing: filler, AI vocabulary, em dashes, mannered prose, and more. The rules are in [skills/unslop/SKILL.md](skills/unslop/SKILL.md).

Forked from the `unslop` skill in [pstack](https://github.com/cursor/plugins/tree/main/pstack) (cursor/plugins at `2eaf465`), MIT licensed. This version drops `disable-model-invocation`, so agents apply it on their own instead of waiting for `/unslop`.

## Install

```sh
npx skills add StivenKN/unslop
```

Or copy `skills/unslop` into `~/.claude/skills/` (Claude Code) or `~/.agents/skills/` (Codex and other agents).
