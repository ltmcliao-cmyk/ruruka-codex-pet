# RuRuKa Codex Pet

RuRuKa is a custom animated desktop pet for Codex.

## Preview

| `idle` | `running-right` | `running-left` |
| --- | --- | --- |
| ![idle](previews/gifs/idle.gif) | ![running-right](previews/gifs/running-right.gif) | ![running-left](previews/gifs/running-left.gif) |

| `waving` | `jumping` | `failed` |
| --- | --- | --- |
| ![waving](previews/gifs/waving.gif) | ![jumping](previews/gifs/jumping.gif) | ![failed](previews/gifs/failed.gif) |

| `waiting` | `running` | `review` |
| --- | --- | --- |
| ![waiting](previews/gifs/waiting.gif) | ![running](previews/gifs/running.gif) | ![review](previews/gifs/review.gif) |

## Install

After RuRuKa is merged into Awesome Codex Pet:

```bash
npx awesome-codex-pet ruruka--ltmcliao-cmyk
```

Windows PowerShell:

```powershell
powershell -NoProfile -ExecutionPolicy Bypass -Command "iwr -UseB https://raw.githubusercontent.com/legeling/awesome-codex-pet/main/scripts/install-pet.ps1 | iex; Install-CodexPet ruruka--ltmcliao-cmyk"
```

macOS / Linux:

```bash
curl -fsSL https://raw.githubusercontent.com/legeling/awesome-codex-pet/main/scripts/install-pet.sh | bash -s -- ruruka--ltmcliao-cmyk
```

## Package

```text
pets/ruruka--ltmcliao-cmyk/
  pet.json
  submission.json
  spritesheet.webp
```

## Awesome Codex Pet

This repository is the public showcase and source package for RuRuKa. The install command above becomes available once the pet is accepted into:

https://github.com/legeling/awesome-codex-pet

## License

RuRuKa pet assets are released under CC BY-NC 4.0 unless stated otherwise.
