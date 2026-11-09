# MailCraft's Taffy

This branch is Taffy `v0.15.1` with the fixes MailCraft's HTML mail reading (through Blitz)
needs, one commit per fix. A fix leaves this list once a Taffy release has it.

| Commit | Fix | Upstream |
|---|---|---|
| `e50ab1fc` | A replaced block child's percentage `width`/`max-width` resolves against zero in its min-content contribution (an inline-block holding a `width:100%` picture shrinks to fit) | on `main`: [#1401](https://github.com/DioxusLabs/taffy/pull/1401) (Blitz issue 1432) |

`e50ab1fc` is upstream's own fix, backported to 0.15.1 (its CHANGELOG line left out).
