# Human Writer

A Claude skill that rewrites text so it reads like a real person wrote it: plain, specific, and
free of AI fingerprints. Works in English and Russian.

It checks copy against five core rules (the stranger test, no slogans, real speech, no invented
facts, concrete offers), removes AI vocabulary and sentence shapes, cleans typography and invisible
characters, and ends with a self-check. A corrections log at the bottom lets the skill learn your
preferences over time.

## Install

**Claude Code:** copy the `human-writer` folder into `~/.claude/skills/`.

```bash
git clone https://github.com/coderMx777/human-writer.git
cp -r human-writer/human-writer ~/.claude/skills/
```

**Claude.ai / Claude Desktop:** download `human-writer` as a zip (Code → Download ZIP, then zip
just the `human-writer` folder) and upload it under Settings → Capabilities → Skills.

## Use

Ask Claude to "humanize this", "make it sound human", or "убери ИИ-шность", or just ask it to write
copy. The skill triggers on its own.

---

## Русский

Скилл для Claude, который переписывает текст так, чтобы он звучал как написанный живым человеком:
просто, конкретно и без признаков ИИ. Работает на английском и русском.

**Установка в Claude Code:** скопируйте папку `human-writer` в `~/.claude/skills/`.
**В Claude.ai:** загрузите папку `human-writer` архивом в Settings → Capabilities → Skills.

Использование: попросите «сделай по-человечески», «убери ИИ-шность» или просто попросите написать
текст. Скилл подключится сам. В конце файла есть журнал правок: дописывайте туда свои «нет», и
скилл будет учиться.
