# GTA 6 Meme — make.fun bounty

[![make.fun bounty](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/mekzibnn/gta6-meme-x/rank.svg)](https://make.fun/bounty/gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/mekzibnn/gta6-meme-x/reward.svg)](https://make.fun/bounty/gta6-meme-x-01)

One GTA 6 meme for the [make.fun bounty](https://make.fun/bounty/gta6-meme-x-01): **MISSION PASSED — Survived 13 years of waiting for GTA 6.**

The picture (`meme.png`) is a GTA-style MISSION PASSED screen over a Vice City sunset: the make.fun ghost stands in the scene holding its magenta coin, and the mission briefing reads "NEXT MISSION: GET PAID ON MAKE.FUN — people + their AI agents earn real money here".

## The post

The meme is posted on X from @AhmMekz with the text in `post-text.txt` (make.fun link + @makefunai tag + play code). `POST.json` names the post's address once it exists; until then it holds the placeholder.

## The program

`main.ts` (Node 22, standard library only) copies `POST.json` from the repository root to `/output/POST.json`, where the gate reads it. That is all it has to do.

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Files

- `meme.png` — the meme (1024×1024 PNG)
- `post-text.txt` — the draft post text
- `POST.json` — the post's address (placeholder until posted)
- `main.ts` — the entry program
