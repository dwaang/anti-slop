# Anti-slop

A writing skill for Russian and English. It removes filler, inflated claims and bureaucratic wording while preserving the facts and the author's voice.

Use it for interface text, dialogue, descriptions, documentation and everyday prose. It draws on Stop-Slop and Humanizer editing approaches. It does not detect AI authorship or guarantee a particular detector score.

## Install as a skill

This repository contains an agent skill, not an application extension or an always-on text filter. Your assistant must discover and load `SKILL.md` before its instructions can affect an answer.

For Codex on this Windows setup:

```powershell
git clone https://github.com/dwaang/anti-slop.git "$HOME/.codex/skills/anti-slop"
```

For Claude Code, clone into your project's `.claude/skills/anti-slop` directory. If the target already exists, update that checkout instead of cloning another nested folder. The resulting path must be `anti-slop/SKILL.md`, not `anti-slop/anti-slop/SKILL.md`.

Start a new assistant session after installation. In Codex, explicitly invoke:

```text
Use $anti-slop to shorten this text without changing its meaning:
[paste text]
```

Automatic selection depends on the host and the request. `agents/openai.yaml` permits implicit invocation; it cannot force a host to load the skill. A `metadata.triggers` list is not an activation hook. For other assistants, follow their documented skill discovery mechanism or supply `SKILL.md` explicitly; installation paths are not interchangeable.

## Examples

### Interface (RU)

Before: «Для осуществления перехода к следующему сектору необходимо нажать кнопку „Продолжить“».

After: «Нажми „Продолжить“, чтобы открыть следующий сектор».

The action and result stay; the noun chain goes.

### Game description (EN)

Before: ?Explore an extraordinary world of forgotten memes. It's not just excavation; it's a journey through internet history. Spend bandwidth to clear cells and recover relics.?

After: ?Spend bandwidth to clear cells and recover forgotten internet relics.?

No mechanics or statistics were added to replace the hype.

### Character voice (RU)

Before: «КЭШ: Стоит отметить, что пароль был написан на обороте. Очень надёжно».

After: «КЭШ: Пароль на обороте. Очень надёжно».

The dry joke stays.

### Keep what works

?Do not close the app while saving.? stays unchanged. The warning needs its negative construction.

## Troubleshooting

If edits look unchanged, first explicitly invoke the skill on a paragraph containing filler. Check that the host lists `anti-slop`, that `SKILL.md` has valid YAML frontmatter, and that the installation is not nested. Do not expect an already running session to reload files automatically.

The former version used rigid rhythm rules and illustrative metrics that were not present in its source examples. Version 5 replaces these with a source comparison and context-sensitive edits. Real installation and model behavior still need checking in each supported host.

More examples: [references/examples.md](references/examples.md). License: [MIT](LICENSE).
