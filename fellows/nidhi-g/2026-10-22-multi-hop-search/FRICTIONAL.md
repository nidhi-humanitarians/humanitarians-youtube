# Frictional Log — Multi-Hop Search: Connecting the Pieces (Part 2 of 2)

Fellow: Nidhi Grover · Project: Iacon Autonomics (RL Environment) · Folder: `2026-10-22-multi-hop-search`
Counts toward: Week 4 (2026-10-14 – 2026-10-20), STEM/AI video, completed late (2026-10-22)
Project repository: [agentic-repl](https://github.com/nidhi-humanitarians/agentic-repl)

---

## 2026-10-20 — First version (files since deleted)
*(Written late on 2026-10-24; describes work from 2026-10-20, from my account.)*

- **What I was working on:** [Nidhi: the original approach for this video.]
- **Where it resisted / what I did next:** Parts of the video were generated, then the approach was reworked and the video recreated on 2026-10-22. The files from this pass were deleted, so no renders or logs survive. [Nidhi: what was wrong with the first approach, and who flagged it.]
- **Claude / others:** [Nidhi.]
- **Evidence:** None kept (files deleted). Recorded from my account. · [HOURS: Week 4](../HOURS.md#week-4--2026-10-14-to-2026-10-20)

## 2026-10-22 — Reworked as Part 2 of the series
*(Written late on 2026-10-24; describes work from 2026-10-22, ~17:40–22:20.)*

- **Tried / expected:** Recreate it as Part 2 of the series: the fixes for points 6–9, plus citations (10) and privacy (11). Edits I asked for: stress why citations matter in B07, and spell out IRCoT in full. I accepted the proposed narration trims and asked for an update at least every 15 minutes.
- **Where it resisted / what I did next:**
  - 16:9: three runs. Gate V failed (2 major issues), then gate T failed on 2 beats, then everything passed; master ~20:20.
  - 9:16: eight runs. Text-size failures (B05 labels, the outro hyphen), two safe-area failures (B02 caption off by 0.02, B10 footer off by 0.08), and a visual review of frames at ≥405 px that found collisions every gate had passed: "Hop" sitting higher than "Multi", line numbers overlapping words, labels touching card edges, cramped wrapped text. Fixing those meant re-rendering 10 scenes. Master ~22:20.
  - About 4 h 40 m from script approval to the last master; the extra ~2 h on 9:16 was fix rounds.
- **Claude / others:** As with Part 1, I gave Claude the context and source material, and it turned them into the script and both builds. I edited the script (B07 citations, IRCoT in full) before approving it, and approved the final video. Claude also listed its own mistakes and created `precheck.py` and `gateb.sh`, which run the layout and size checks before any long build (kept in `brutalist-vids/_tools`).
- **Understand now / still don't:** Passing the automated gates doesn't mean a frame looks right, so check frames by eye. Run the cheap checks before the long build. [Nidhi.]
- **Evidence:** [SCRIPT.md](SCRIPT.md) · [FACTCHECK.md](FACTCHECK.md) · [TYPECHECK.md](TYPECHECK.md) · [final/multi-hop-search.verified.json](final/multi-hop-search.verified.json) · [video](https://www.youtube.com/watch?v=rZhI6hPbIOs)
