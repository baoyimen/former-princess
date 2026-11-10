# former-princess

Cursor skills from [gstack](https://github.com/garrytan/gstack) v1.99.0.0 (`6b327148e37134e2628d2d20cd98f33dcbeef51c`), rendered for the Cursor host.

The skills are in `.cursor/skills/`. Each folder has a `SKILL.md`. Ask for the skill by the `name` in that file, for example `office-hours`, `review`, `qa`, `ship`, or the `gstack` router. The helper scripts they call live at `.cursor/skills/gstack` (bin and lib). A skill looks there first, then in `~/.cursor/skills/gstack`.

Compiled browse, design, and PDF binaries are not in this snapshot. Skills that need them say how to build them with gstack's `./setup --host cursor` from a full [gstack](https://github.com/garrytan/gstack) checkout. Planning, review, and the other instruction-driven skills run from the files in this repo. The preamble script degrades safely when a helper is missing.

Upstream is MIT licensed. The license is at `.cursor/skills/gstack/LICENSE`. The snapshot pin is `.cursor/skills/gstack/UPSTREAM`.
