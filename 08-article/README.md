# 08: Article

Write the CSS in `style.css`. The HTML is a small editorial article page. Match `goal.png`.

The point of this one is laying out a page to read well, which is mostly two moves:

- **A centered column at a readable width.** Give `.post` a `max-width` around `60ch` and `margin: 0 auto`. Long lines are the most common thing that makes a page hard to read.
- **Rows that split left and right.** The `.byline` (author and date) and the `.post-foot` are each a flex row with `justify-content: space-between`.

The kicker, headline, and pull quote are already styled. You are only positioning things.

Properties in play: `max-width`, `margin`, `display: flex`, `justify-content: space-between`.
