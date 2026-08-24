# Design direction — decided after auditing both references

## Structure donor: AIthor (fits — B2B service, same content shape)
- 4-step process → maps to GC UK's "ideal timeline / milestones" content
- Numbered FAQ (01/ 02/ ...) → GC UK has 5 real FAQ-shaped Q&As in the advantage section
- 6-item testimonial grid → GC UK has exactly 6 real testimonials
- "Us vs. alternatives" comparison → maps directly onto the real "GooCampus Advantage"
  section, which is already written as a comparison (self vs self-preparation vs
  juggling vendors)

## NOT taking from Forth
Consumer social/events app — tone, playful rounded type, card-feed UI don't fit a
B2B doctor-consulting service. Not pulling structure from it.

## Type (own choice, not copied from either reference)
- Display: Source Serif 4, bold — credibility/editorial gravitas for GMC/visa-heavy
  content. Distinct from AIthor's Halant, distinct from Australia's Urbanist/Inter Display.
- Body: Public Sans — clean, distinct from Australia's Inter, so the two sites don't
  visually collide.

## Colour (measured earlier, from the real logo + official codes)
- #233974 (navy) — ink, headlines, buttons. 11:1 white-on-navy, AA pass.
- #48BB88 / #5FC19D (greens) — decorative only. Both fail AA for text (2.19–2.40:1).

## Motion
Scroll-triggered fade+rise reveals, same category both references use (Framer
Motion there, GSAP + IntersectionObserver here) — same hardened pattern already
proven on the Australia build: visible-by-default, animates from hidden, no
stale-ScrollTrigger-position failure mode.

## Motif
A milestone/roadmap connecting line through the process section — GC UK's own copy
is literally about "ideal timeline," "milestones," "avoid last-minute planning."
