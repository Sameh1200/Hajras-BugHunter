# Hajras-BugHunter

Self-contained **Hajras** skill bundle for bug hunting and external red-team work.

**Identity:** Hajras / Sameh1200  
**Upstream origin (rebranded):** elementalsouls/Claude-BugHunter — Claude plugin removed; all product identity rewritten to Hajras.

## Layout

```
skills/          # 80+ methodology & hunt skills
commands/        # slash-style workflow commands
cbh/             # terminal CLI runner
engine/          # agent / memory / skill map
docs/            # architecture, usage, verification
scripts/         # install & maintenance helpers
eval/            # evaluation harness
research/        # research notes
```

## Install

See `INSTALL.md` and `USAGE.md`. Paths use `~/.hajras/` (not Claude directories).

## Skills already in Sameh1200/HajrasSkillsToolsMCP

Tool-level `skill.md` packs (nmap, subfinder, httpx, nuclei, …) live in the sister repo under `skills/<tool>/skill.md`.

## License

MIT (see LICENSE). Content notices preserved under LICENSE-CONTENT / NOTICE where required.
