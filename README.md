# Range Bets — solo

The standalone, self-paced version of **Range Bets** (d.MBA *Prototyping with
Numbers* module). One player, one file.

Eight rounds. Each is a "how many…?" question with three facts (**anchors**).
You never give a single number — you drag a **range** on a log scale. A narrower
range pays more, but only if the real answer is inside it; a miss costs points
for every ×10 you're out. One free **check** per round tests the anchor you
trust least — some are planted traps. One round lets you commit to a single
number for a flat payout (the "CFO round").

At the end, results are emailed to the player and the d.MBA team via the shared
EmailJS templates (same setup as the other solo games).

Round content and scoring mirror the facilitated multiplayer version
(`range-bets`), fact-checked 2026-10-14.

## Run

It's a single static file — just open `index.html`, or serve the folder:

```bash
python3 -m http.server 8097   # then open http://localhost:8097
```

No build step, no server code.
