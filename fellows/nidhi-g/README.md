# Nidhi Grover — Humanitarians AI Fellow

**Project:** Iacon Autonomics (RL Environment project)<br>
**Project Managers:** Dhruv Patel, Shilpa<br>
**Current agreement:** 2026-09-14 – 2026-10-31<br>
**GitHub:** [@nidhi-humanitarians](https://github.com/nidhi-humanitarians)<br>
**LinkedIn:** [nidhirg57](https://www.linkedin.com/in/nidhirg57/)

## About
I graduated from North Carolina State University (NCSU) with a B.S. in Computer Science, concentrating in Artificial Intelligence, with a minor in Statistics. At Humanitarians AI I work on the Iacon Autonomics (RL Environment) project. I started with a multi-hop retrieval-augmented generation (RAG) subproject, which I'm now wrapping up. I'm also building a habit compiler (Myelin) to make LLM pipeline tasks faster and cheaper to run.

## Projects

| Project | What it is | Repository | Status |
|---|---|---|---|
| **Multi-hop RAG / agentic search** | Can an agent answer questions over documents far too long to read by writing code to search them? A Pi-style agent loop with a Python REPL, tested on the BABILong multi-hop benchmark. | [agentic-repl](https://github.com/nidhi-humanitarians/agentic-repl) | Testing, debugging and write-up |
| **Myelin (LLM habit compiler)** | Spots repetitive decisions in agent traces and compiles them into fast, deterministic code that abstains when unsure, so the LLM is called only when needed. | [myelin](https://github.com/nidhi-humanitarians/myelin) | Initial research, technical specification and scaffolding done |

## Research / Project Plan

| Project | Deliverable | Target date | Status | Repository |
|---|---|---|---|---|
| Multi-hop RAG / agentic search | Finish testing and debugging the code-REPL search agent on the BABILong benchmark, then write up the results, failure modes and proposed fixes | — | In progress | [agentic-repl](https://github.com/nidhi-humanitarians/agentic-repl) |
| Myelin (LLM habit compiler) | First working version of the habit compiler: detect repeated decisions in agent traces and compile them into deterministic code that abstains when unsure | 2026-10-27 | In progress | [myelin](https://github.com/nidhi-humanitarians/myelin) |

## Weekly Evidence Index

Detailed weekly records: [HOURS.md](HOURS.md). Each video folder has a README (links to the videos) and a FRICTIONAL.md (process log).

| Week | Start | End | Actual hours | Video links | Log and work evidence |
|---|---|---|---|---|---|
| 0 | 2026-09-14 | 2026-09-22 | — | None (agreement signing period) | Signed agreement received 2026-09-22 |
| 1 | 2026-09-23 | 2026-09-29 | 5 | None | [HOURS: Week 1](HOURS.md#week-1--2026-09-23-to-2026-09-29) |
| 2 | 2026-09-30 | 2026-10-06 | 20 | None (two failed setup test reels) | [HOURS: Week 2](HOURS.md#week-2--2026-09-30-to-2026-10-06) · [binary-search-test](2026-10-02-binary-search-test/) · [ribosomes-read-mrna](2026-10-02-claude-liam-ribosomes-read-mrna/) |
| 3 | 2026-10-07 | 2026-10-13 | 20.2 | [Progress: Brutalist Installation](https://www.youtube.com/watch?v=t2tT4li77jM) · [STEM: Why RAG fails for complex texts](https://www.youtube.com/watch?v=bgagiyyImeI) *(made late, 2026-10-22)* | [HOURS: Week 3](HOURS.md#week-3--2026-10-07-to-2026-10-13) · [Brutalist, Installed. log](2026-10-12-brutalist-installed/FRICTIONAL.md) · [Stuff It or Search It? log](2026-10-22-stuff-or-search/FRICTIONAL.md) · [agentic-repl](https://github.com/nidhi-humanitarians/agentic-repl) |
| 4 | 2026-10-14 | 2026-10-20 | 20 | [Progress: Multi Hop Reasoning Project Update](https://www.youtube.com/watch?v=q5kbQpRghHs) · [STEM: Multi Hop Search](https://www.youtube.com/watch?v=rZhI6hPbIOs) *(completed late, 2026-10-22)* | [HOURS: Week 4](HOURS.md#week-4--2026-10-14-to-2026-10-20) · [Search, Don't Read. log](2026-10-20-search-dont-read/FRICTIONAL.md) · [Multi-Hop Search log](2026-10-22-multi-hop-search/FRICTIONAL.md) · [agentic-repl](https://github.com/nidhi-humanitarians/agentic-repl) |
| 5 | 2026-10-21 | 2026-10-27 | 13 (so far) | Progress video in progress | [HOURS: Week 5](HOURS.md#week-5--2026-10-21-to-2026-10-27-in-progress) · [myelin](https://github.com/nidhi-humanitarians/myelin) |

**STEM/AI playlist:** [Humanitarians AI Conceptual Videos](https://www.youtube.com/playlist?list=PLBfwlskHBwRM)<br>
**Progress playlist:** [Humanitarians AI Update Videos](https://www.youtube.com/playlist?list=PLMg75wq-4wVw)<br>
**Renders:** [Google Drive](https://drive.google.com/drive/folders/1urwoGwLCSoS4XG3U7dz-HtGePkXyDaGY)

## Completed Results

1. **Working Brutalist setup and four published videos**: After two failed setup attempts, I got Brutalist running on Windows (isolated Python 3.12 environment, a Windows `npx` fix) and produced four videos in 16:9 and 9:16, from content and materials I provided and scripts I reviewed, edited and approved. Evidence: [Brutalist, Installed.](2026-10-12-brutalist-installed/) · [Search, Don't Read.](2026-10-20-search-dont-read/) · [Stuff It or Search It?](2026-10-22-stuff-or-search/) · [Multi-Hop Search](2026-10-22-multi-hop-search/)
2. **Agentic search test harness (multi-hop RAG)**: Set up a repository with a Pi-style agent loop and a Python REPL (search helpers such as `grep` and `read_lines`), and tested it on BABILong qa2 at 128k tokens. On the first test question, it found the scattered facts and answered correctly, citing the lines it used. Evidence: [agentic-repl](https://github.com/nidhi-humanitarians/agentic-repl)
3. **Myelin: initial research and technical specification**: Completed preliminary research, a technical design specification, and the basic repository scaffolding and testing for the LLM habit compiler. Evidence: [myelin](https://github.com/nidhi-humanitarians/myelin) · [design specification](https://github.com/nidhi-humanitarians/myelin/blob/main/docs/DESIGN_SPECIFICATION.md)

## Reviews
Brutalist video reviews: [to be added]

## Renewal
Renewal report: [RENEWAL.md](RENEWAL.md)

## Outstanding Issues
- **Agreement:** The agreement period is listed as 2026-09-14 – 2026-10-31, but the completed, signed contract was received on 2026-09-22 at 21:15. Per program guidance, no work was performed before the signed agreement was in hand, so this record covers 2026-09-23 onward.
- **Week 1 below 20 hours:** 5 hours, the first week after signing, spent on onboarding and project assignment.
- **Brutalist setup:** I had a considerable number of issues setting up Brutalist (two failed attempts in Week 2, about 7 hours each) and discussed them with my project managers. These issues affected my ability to produce the weekly videos: there are no weekly videos for Weeks 1–2, and the Week 3 STEM/AI video was made late.
- **Project change:** My initial project, the Kaggle Gemma Hackathon, was dropped on 2026-10-06 because of differing competency expectations from the project managers. I moved to the multi-hop RAG problem, and later received the Myelin assignment.
- **Late videos:** The Week 3 STEM/AI video (*Stuff It or Search It?*) was made on 2026-10-22. The Week 4 STEM/AI video (*Multi-Hop Search*) was reworked and completed on 2026-10-22. Each video's README has a late note.
- **Week 5:** In progress; the progress video and STEM/AI video are not finished yet.
