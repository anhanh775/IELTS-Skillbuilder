# IELTS Skill Builder (4.5+) – 30 Sessions

- `index.html` – hub page with 30 session tiles.
- `session-02/index.html` – IELTS Short Writing Practice.
- `session-03/index.html` – IELTS Short Speaking Practice (Part 1: Education).

## Adding a session
1. Create `session-NN/index.html` (NN = 01 to 30).
2. In the root `index.html`, edit the `S` array: set `title`, `skill` (lr, wr or sp) and `href:"session-NN/"`.
3. In the new page, add a link back to the hub: `<a href="../" class="back">← All sessions</a>`.

Use a different `localStorage` key prefix in each session (Writing uses `sw-`, Speaking uses `sp`).
