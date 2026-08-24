# GC UK colour palette — official, as supplied

| Role | Name | Hex | Notes |
|---|---|---|---|
| Ink / text / buttons | Dark moderate blue | `#233974` | White text on this = 11.00:1 (AA pass). Also passes as text on white/paper (10.26–11.00:1). |
| Accent (decorative only) | Moderate cyan-lime green | `#48BB88` | 2.40:1 white-on-it, 2.24:1 as text on paper — FAILS AA either way. Never carries text. |
| Accent (decorative only) | Moderate cyan-lime green (light) | `#5FC19D` | 2.19:1 white-on-it, 2.04:1 as text — FAILS AA either way. Never carries text. |

## Role split (measured, not guessed)
- **#233974** — headlines, body text, primary buttons, anything carrying white text.
- **#48BB88 / #5FC19D** — underlines, icon fills, chip borders, the roadmap/milestone
  motif's connecting line, small decorative UI. Never text-on-colour or colour-as-text.

This mirrors the Australia site's pattern (bright accent decorative-only, a passing
shade carries buttons) but is cleaner here — the official navy already passes AA on
its own, so no separate darker "button-only" shade needs to be invented.
