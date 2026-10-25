# Frictional Log — Brutalist, Installed.

Fellow: Nidhi Grover · Project: Iacon Autonomics (RL Environment) · Folder: `2026-10-12-brutalist-installed`
Counts toward: Week 3 (2026-10-07 – 2026-10-13), progress video

---

## 2026-10-11 — Starting over: second install, read the error first
*(Written late on 2026-10-24; describes work from 2026-10-11, ~21:00–23:00.)*

- **What I was working on:** Giving up on patching the first install, deleting it, and setting Brutalist up again from a fresh copy. Before this, I watched the detailed Brutalist setup guide. [Nidhi: what made you decide to start over.]
- **Tried / expected:** Asked Claude Code whether this machine had every dependency the pipeline needs. [Nidhi: expectation.]
- **Where it resisted / what I did next:**
  - `./setup` stopped before checking anything: "ElevenLabs reference found — this toolkit is Kokoro-only for narration." It was a false alarm. The matches were in 10 files of example videos inside `youtube/brutalist/` that explain that check. Claude tried running setup with the check removed, and Claude Code's safety mode blocked it. I asked what the error actually was, didn't understand the first explanation, and asked again. Then I decided: "Just move the folder for now." It went to `brutalist-vids/brutalist-playlist/`, uncommitted, so it can be restored.
  - Python 3.14 was too new for the animation library (`manim<0.19` requires < 3.13), and `python3` opened the Microsoft Store prompt on Windows. Fix: a Python 3.12.10 virtual environment with a `python3` copy, then `./setup --install`.
  - Readiness after install: audio, captions, Manim, Remotion, compile and fonts ready; equations blocked (needs LaTeX, not needed yet).
  - A local fix was needed for Windows: `remotion_scenes.py` now finds `npx` with `shutil.which`.
- **Claude / others:** I gave Claude Code the goal and the errors to work from. It diagnosed them, explained them until they made sense, and ran the environment setup and install at my request ("Could you do it for me?"). I chose the fixes, including moving the folder rather than editing the check. [Nidhi: discussion of the setup issues with Dhruv / Shilpa, with date.]
- **Understand now / still don't:** Now: read the error before fixing anything; gates are checks, not bugs; isolate Python per project. The toolkit's maintainers fixed both the ElevenLabs check and the Python requirement on 2026-10-11 (commits by meenuviji); my copy came before those fixes. [Nidhi: still unclear.]
- **Evidence:** [FACTCHECK.md](FACTCHECK.md) (every claim traced to real output) · `brutalist` git reflog (fresh clone of `nikbearbrown/brutalist.art`) · `brutalist` commits of 2026-10-11 ("setup: skip youtube/ and .venv/ in the ElevenLabs guard"; "setup: require python3 >= 3.10")

## 2026-10-11 → 10-12 — Making the video as proof the install works
*(Written late on 2026-10-24; describes work from 2026-10-11 23:13 to 2026-10-12 ~15:45.)*

- **Tried / expected:** A test video about the install itself, so that a working video would prove the install was correct. I asked for a plan, the important paths, and the right video type before anything ran.
- **Where it resisted / what I did next:**
  - Chose Bella as the voice and @HumanitariansAI as the channel; no dates or times on screen.
  - Script v2 edits I asked for: say I used Claude Code for both installs; condense the second install to 2–3 beats; drop the "hidden assumptions" framing and call it an agentic video-creation pipeline using Claude. Approved 2026-10-12 00:03.
  - Gate T passed 03:24 (one advisory: B07 narration reads the card aloud). 16:9 master ready ~03:35. Then I asked for the 9:16 version (started ~11:19); it was done by ~15:45.
- **Claude / others:** I provided the story of both installs and the evidence behind it. Claude translated that into a script, beat sheet and scenes, and ran the build. I reviewed the script, made the edits above, approved it, and approved the final video.
- **Understand now / still don't:** [Nidhi: e.g., how long a full build takes; whether you can go straight to 9:16 next time.]
- **Evidence:** [SCRIPT.md](SCRIPT.md) · [TYPECHECK.md](TYPECHECK.md) · [STATUS.md](STATUS.md) · [final/brutalist-installed.verified.json](final/brutalist-installed.verified.json) · [video](https://www.youtube.com/watch?v=t2tT4li77jM)
