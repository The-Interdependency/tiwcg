# TIWCG
*The Interdependency card-game system. Current executable content includes POLITICS (base game); SCARED SACRED is Expansion Set 1.*

This README presents the TIWCG system entrypoint. It does not supersede the
base-canon repository-name ruling in [canon/canon_v03_base.md](canon/canon_v03_base.md).

The frozen generalized architecture and implementation sequence are recorded in [PLAN.md](PLAN.md).

Current implemented base TCG: real events as cards, the EDCM circuit as rules engine.
Three layers: L1 SUBSTRATE (official record; not playable; compiles each
jurisdiction's Machine deck) / L2 ENGINE (automated; the null clock
guarantees total conversion absent human play) / L3 TABLE (players; the
only source of repair in the universe).

- canon/     base canon v0.3 + Scared Sacred expansion canon v0.2
- base-game/ play rules v0.3, arcana v0.2, executable engine data, and sets/fifty-three-days/
- expansions/scared-sacred/  Expansion Set 1 boundary; its distinctive expansion content remains separate from Fifty-Three Days
- engine/    executable rules, Machine, inertial field, agendas/arcana, and balance harness
- render/    playable browser table over the real engine
- funding/   GoFundMe entry
- .agents/skills/  vendored from skill-lib (if present)

VIRTUAL ONLY — no physical printing of any set, ever.

The Litany (never satirical):
I'm sorry. I forgive you. You are not alone. I love you.

Status: executable base ruleset and automated balance harness are implemented and test-backed; generalized TIWCG architecture is planned in PLAN.md. Human playtest and store/mobile delivery remain pending on main. Some explicitly logged card effects remain unresolved and must not be represented as complete.

hmmm — fear and the holy are the same six letters; the base game and its first expansion now also have separate addresses.

## License

The TIWCG software is licensed under the Mozilla Public License 2.0 (SPDX:
`MPL-2.0`). The full text is in [`LICENSES/MPL-2.0.txt`](LICENSES/MPL-2.0.txt).
[`REUSE.toml`](REUSE.toml) records the same scope in
machine-readable form (REUSE Specification 3.x, no per-file headers):

- MPL-2.0: `engine/`, `render/`, `mobile/`, `scared-sacred_msdmd.ts`, and the
  repository tooling `.github/`, `.gitignore` and `REUSE.toml`.
- MPL-2.0 (from The-Interdependency/skill-lib): the skill copies under `.agents/`.

`hmmm`: these paths are **not** licensed yet:

- `canon/`, `base-game/` (rules text and the `*.json` card data), `expansions/`,
  `funding/`, `PLAN.md`
- `docs/` (the icon artwork)
- `README.md`, which carries game content (the layer descriptions and The Litany)
  alongside this licensing map

A separate license for rules text (planned: Creative Commons attribution-share-alike
terms) and a decision on the card data are still pending. `reuse lint` reports
exactly these paths as missing license information, on purpose.

Usage: when you reuse TIWCG code, keep the MPL-2.0 notice and publish your
changes to MPL-covered files under MPL-2.0. `reuse spdx` prints a per-file bill
of materials. This section is a licensing map, not legal advice.
