# Colson's Big 13 — Birthday Game Suite

One Vercel project, three pages:

| File | What it is | Where it serves |
|---|---|---|
| `index.html` | Are You Smarter Than a 6/7 Grader? — the party game board | areyousmarterthanasixsevengrader.vercel.app |
| `colson-bowl-xiii.html` | Colson Bowl XIII — Food Pyramid drag-and-drop championship (opens from the game's Kickoff tile) | /colson-bowl-xiii.html |
| `colson-big-13_index.html` | The California trip countdown — the QR code's destination | colson-big-13.vercel.app (routed by vercel.json) |

`vercel.json` routes the `colson-big-13.vercel.app` domain to the countdown page so the printed QR code works.

Host PIN for the game's Host Key: the birthday, four digits.

Do not rename files — the QR code and the game's Kickoff link depend on these exact names.
