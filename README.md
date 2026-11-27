# IELTS Skill Builder (4.0+) – 30 Sessions

- `index.html` – hub page with 30 session tiles.
- `session-02/index.html` – IELTS Short Writing Practice.
- `session-03/index.html` – IELTS Short Speaking Practice (Part 1).
- `session-03/game/index.html` – warm-up game “Guess the IELTS Speaking band” (small GAME button inside tile 03).

## Adding a session
1. Create `session-NN/index.html` (NN = 01 to 30).
2. In the root `index.html`, edit the `S` array: set `title`, `skill` (lr, wr or sp) and `href:"session-NN/"`. For small buttons inside a tile (like GAME), add `extras:[{label:"Game",href:"session-NN/game/",icon:"device-gamepad-2"}]`.
3. In the new page, add a link back to the hub: `<a href="../" class="back">← All sessions</a>`.

Use a different `localStorage` key prefix in each session (Writing uses `sw-`, Speaking uses `sp`).
