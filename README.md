# Ponytail for Grok

Lazy senior dev mode for Grok. The best code is the code you never wrote.

~54% less code · ~20% cheaper · ~27% faster · 100% safe

## Install

```bash
grok plugin install DietrichGebert/ponytail --trust
```

Then enable:

```toml
# ~/.grok/config.toml
[plugins]
enabled = ["ponytail"]
```

Or via UI: `/plugins` → enable `ponytail`.

Restart the session. Use `/ponytail`, `/ponytail lite`, `/ponytail ultra`, `/ponytail-review`, `/ponytail-audit`, `/ponytail-debt`, `/ponytail-gain`, `/ponytail-help`.

## Core ladder

1. Does this need to exist? → skip (YAGNI)
2. Already in codebase? → reuse
3. Stdlib? → use it
4. Native platform feature? → use it
5. Installed dependency? → use it
6. One line? → one line
7. Only then: minimum code that works

## Files

- `skills/ponytail/SKILL.md` – main skill
- `skills/ponytail-review/SKILL.md`
- `skills/ponytail-audit/SKILL.md`
- `skills/ponytail-debt/SKILL.md`
- `skills/ponytail-help/SKILL.md`
- `skills/ponytail-gain/SKILL.md`
- `AGENTS.md` – always-on instructions
- `.grok-plugin/marketplace.json`
- `plugin.json`

Source: https://github.com/DietrichGebert/ponytail