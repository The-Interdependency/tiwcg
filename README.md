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
`MPL-2.0`). The full text is in [`LICENSE`](LICENSE). "Software" here means
`engine/`, `render/`, `mobile/` and `scared-sacred_msdmd.ts`. The skills under
`.agents/skills/` are copies from The-Interdependency/skill-lib and keep that
repository's MPL-2.0 license.

`hmmm`: the rules text and game content (`canon/`, `base-game/`, `expansions/`,
`funding/`, `PLAN.md`, `docs/`) are **not** covered by this license yet. A separate
license for rules text (planned: Creative Commons attribution-share-alike terms) and a decision on the
`base-game/*.json` card data are still pending.

Usage: when you reuse TIWCG code, keep the MPL-2.0 notice and publish your
changes to MPL-covered files under MPL-2.0. This section is a licensing map,
not legal advice.
