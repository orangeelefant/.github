# CLAUDE.md

Projektkontext för Claude Code-sessioner i det här repot.

## Vad det är

GitHub-organisationsprofilen för `orangeelefant`. `profile/README.md` är det som visas
överst på https://github.com/orangeelefant.

Repot heter `.github` på GitHub. Lokalt ligger det som `apps/github-org-profile` så att
det inte blir en dold mapp.

## Stack

Ingen. Bara markdown. Inget bygge, inga beroenden, ingen deploy — GitHub renderar
`profile/README.md` direkt.

## Layout

- `profile/README.md` — **profiltexten som syns publikt**. Det är den här filen som räknas.
- `ABOUT.md` — längre bakgrund, syns inte på profilsidan.
- `AGENTS.md`, `CLAUDE.md`, `CHANGELOG.md`, `TODO.md` — repodokumentation.

## Kommandon

Inga. Redigera markdown, committa, pusha — ändringen syns direkt på profilsidan.

## Konventioner

- Profilen är personlig och engelskspråkig. `ABOUT.md` beskriver Webraketen-flottan.
- **Länka aldrig till `github.com/Webraketen`** — organisationen togs bort 2026-07-30
  och URL:en ger 404. Länka till https://webraketen.se i stället.
- Lägger du till ett projekt i profilen: kontrollera att länken lever först.

## Klart betyder

1. Länkarna i ändringen är verifierade (inga 404).
2. `CHANGELOG.md` uppdaterad under `[Unreleased]`.
3. `TODO.md` stämd av.
4. Committat och pushat till `main`.

Hela agentkontraktet står i `AGENTS.md`.
