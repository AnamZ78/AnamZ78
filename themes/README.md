# Theme rotation

`README.md` at the repo root is overwritten daily by the **Rotate README theme** workflow, which picks one of these by day of year:

| Theme | Mood |
|---|---|
| `catppuccin.md` | soft & pastel |
| `dracula.md` | bold & loud |
| `gruvbox.md` | warm retro terminal |
| `paper.md` | minimal, light, editorial |

`tokyonight.md` is kept here but not in the rotation. To add or remove a theme, edit the `THEMES` array in `.github/workflows/rotate-readme.yml`.

To force one right now: Actions → Rotate README theme → Run workflow → type its name.

**Edit content in all theme files**, not in the root `README.md`, or the change is lost at the next rotation.
