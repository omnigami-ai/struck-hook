# Struck hook · omnigami

The old way in three huge lines, struck out.

A five-second opener: the problem your product solves lands in three huge lines on the beat, then every line is struck through in your brand colour and held. It sets up the turn to your product.

Watch it play live, and change its words, at [omnigami.ai/skills/struck-hook](https://omnigami.ai/skills/struck-hook).

## Install

In Claude Code:

```
/plugin marketplace add omnigami-ai/skills
/plugin install omnigami-struck-hook@omnigami
```

With the skills CLI, for Claude Code and other agents that read SKILL.md:

```bash
npx skills add omnigami-ai/struck-hook
```

Or copy `skills/struck-hook/` into your agent's skills folder (for Claude Code, `~/.claude/skills/struck-hook/`). Then ask:

```
Make a struck-hook opener for https://your-product.com
```

## What it runs

The skill works on your computer. It runs the Node scripts in `skills/struck-hook/scripts/`: they open your product's pages in a local headless browser to capture its real screens, then render the film with that browser and ffmpeg, writing MP4s and an editable HTML film to your project. It sends nothing to omnigami or anyone else, and uses no network beyond loading your own product's pages and the fonts and assets in this folder.

## You need

- Claude Code with Opus 5.5
- Node 20 or later
- ffmpeg
- Chrome, Chromium, Edge or Brave

None beyond your Claude plan’s usage. Node, ffmpeg and the browser are free.

## Licence

Free to use. Use the films and anything else the skill makes for anything, commercial work included. Don't redistribute the skill. See [LICENSE.md](LICENSE.md). The bundled fonts keep their own licence (SIL Open Font License, beside them in `reference/assets/fonts/`).

## Credits

Style inspired by the grammar of Figma’s “Figma Motion” (https://x.com/figma/status/2069827742800253230), ElevenLabs’ “Reception” (https://x.com/ElevenLabs/status/2100262886916358361), @LexnLin’s “Tessel” (https://x.com/LexnLin/status/2104148233106723099): an independent style study; none of them made or endorsed this skill. Its example shows Lamplit, a fictional company made for omnigami’s examples, with sample data.

omnigami is not affiliated with Anthropic. More skills at [omnigami.ai](https://omnigami.ai).
