# AI and design decisions

## Day 7

### Decision: 2x2 card grid
- What: chose `grid-template-columns: repeat(2, 1fr)` instead of three columns.
- Why: four project cards fill a 2x2 grid evenly; three columns would leave
  one orphan card alone on the second row.

### Decision: kept the white card style from the sections
- What: cards reuse the same white background and radius as the page sections.
- Why: consistency; the cards should feel like part of the same site,
  not a new design bolted on.

## Day 8

### Decision: 200ms card lift, 250ms nav colour
- What: transitions kept between 200ms and 250ms.
- Why: fast enough to feel responsive, slow enough to feel smooth.
  Longer felt sluggish when tested.

### Decision: soft mint hover colour on the dark nav
- What: nav links hover to #7fe0c0 instead of the section green #0e7a5f.
- Why: the darker green disappears against the navy header; the lighter
  mint keeps contrast strong.
