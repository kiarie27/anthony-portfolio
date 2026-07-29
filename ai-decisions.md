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
