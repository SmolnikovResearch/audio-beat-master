# Smolnikov Research Skill - `audio-beat-master`

> **Category:** Video & Audio Production · **License:** MIT · **Author:** [Smolnikov Research Center](https://github.com/SmolnikovResearch)

**EN:** Synthesize beat grids and normalize audio to -16 LUFS.

**RU:** Синтез бит-сетки, суб-120 Гц детектор ударных онсетов и нормализация громкости ebur128.

---

## On-Demand Activation & Lazy Loading (`on-demand.json`)

This skill stays **disabled by default** (`auto_load_on_startup: false`) and loads dependencies/checkpoints strictly when you enable and run it:

| Component | Requirement |
|---|---|
| System binaries | `ffmpeg` |
| Python packages | `none (stdlib)` |
| Model checkpoints | `none` |

## Installation in CapyAgent

```bash
capyagent skills install SmolnikovResearch/audio-beat-master/skills/audio-beat-master
```

Or copy this directory into `~/.capyagent/skills/` (or `~/.agents/skills/`).

## Check Status & Bootstrap Dependencies

```bash
python3 scripts/optional_skill_bootstrap.py audio-beat-master --status
python3 scripts/optional_skill_bootstrap.py audio-beat-master --install
```

See [`SKILL.md`](SKILL.md) for agent instructions and workflow examples.

## Related

- Full multi-skill catalog: [SmolnikovResearch/skills](https://github.com/SmolnikovResearch/skills)
- License: [MIT](LICENSE)
