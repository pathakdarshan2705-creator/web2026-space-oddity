# 09: Front page

Write the CSS in `style.css`. This is a magazine front page, laid out entirely with flexbox. Match `goal.png`.

This is the one where flexbox lays out a whole page. Four moves:

- **The page is a column.** `.paper` is a flex column so the masthead, stories, and footer stack top to bottom with a gap.
- **The masthead and footer are rows.** Title on the left, issue or note on the right: `display: flex; justify-content: space-between; align-items: center`.
- **The stories are a row.** `.stories` is a flex row with a gap. The lead gets `flex: 2` and the rail gets `flex: 1`, so the lead is about twice as wide.
- **The rail is a column.** `.rail` is itself a flex column so its two small stories stack.

That last part, a column inside a row, is the move that builds most real page layouts. Grid will make this even easier next week, but flexbox gets you a long way first.

Properties in play: `flex-direction`, `justify-content`, `gap`, `flex: 2` and `flex: 1`.
