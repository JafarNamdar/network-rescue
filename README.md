# Network Rescue: The UK Distribution Challenge
Interactive supply chain network design game for students. The notebook runs code-free via Voila + Binder.

## 🎮 Play the game
Play in class, then finish at home: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/JafarNamdar/network-rescue/HEAD?urlpath=voila%2Frender%2FNetwork_Rescue_Game_student.ipynb)

Click the badge above (or use the direct link below it, if the badge doesn't render on your device):

Game: https://mybinder.org/v2/gh/JafarNamdar/network-rescue/HEAD?urlpath=voila%2Frender%2FNetwork_Rescue_Game_student.ipynb

First click can take 2–5 minutes to build (it's setting up a private Python environment with the Gurobi optimizer just for you) — that's normal, just wait for it. After that it usually loads in about a minute.

**Backup — if Binder is slow or down:** [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JafarNamdar/network-rescue/blob/main/Network_Rescue_Game_student.ipynb)

Colab: https://colab.research.google.com/github/JafarNamdar/network-rescue/blob/main/Network_Rescue_Game_student.ipynb

In Colab, sign in with a Google account and click **Runtime → Run all**. The code stays folded away; you'll see the same control panel and answer boxes. If the answers download link doesn't work in Colab, use **File → Download → Download .ipynb** instead and submit that file.

## How to play
1. Read the mission, presentation guide, rubric, and problem description at the top of the page.
2. Type your team name and members in the boxes at the top.
3. Use the control panel: open a panel, change a value, and click **Solve with Gurobi**. You'll see the total cost, which depots are used, shortages and service levels, the shipping routes, and a network diagram.
4. Click **Reset to baseline** before every new scenario, then change only what the question asks.
5. Type your answers in the ✏️ boxes under each question.
6. At the end of the page, click **Prepare my answers file**, then the download link. You'll need this file for your submission.

⚠️ **Nothing is saved automatically.** If the page sits idle for about 10 minutes, the session closes and typed answers are lost. Download your answers file often (you can download it as many times as you want).

No code is shown anywhere on the page — if you ever see raw Python instead of the game text, boxes, and buttons, refresh the page or re-click the link above.

## Course flow
**The game (in class + take-home)** — `Network_Rescue_Game_student.ipynb`
Teams act as consultants for a company with 2 factories, 6 candidate depots, and 6 customers. An optimization model finds the cheapest network for any inputs students choose. Four required scenarios, each with two specific questions:

1. **Network design** — today's optimal network and its bottleneck.
2. **Disruption risk** — a depot fire or a factory strike, with and without the flexibility to open a backup depot.
3. **Planning with vs. without risk** — how the decision changes when reliability is included.
4. **Demand uncertainty** — low, base, and high demand, and the cost of being locked into today's network.

Plus a menu of 8 elective questions (teams pick 2, so presentations differ) and a required strategy recommendation. Teams present in 7–8 minutes with at most 6 slides; the presentation guide and rubric are inside the notebook.

**Submit (one per team):** the downloaded answers file and the slide deck.

## Setup (one-time, for the instructor)
Already done for this repo — the notebook and `requirements.txt` are at the repo root. The Binder link pattern is:

`https://mybinder.org/v2/gh/JafarNamdar/network-rescue/HEAD?urlpath=voila%2Frender%2FNetwork_Rescue_Game_student.ipynb`

To generate/verify a link yourself on mybinder.org:

- GitHub repository name or URL: `JafarNamdar/network-rescue`
- Git ref: `HEAD`
- File to open: change the dropdown from **File** to **URL**, then enter `voila/render/Network_Rescue_Game_student.ipynb`
- Click **Launch**, and use the auto-generated shareable URL (not the session-specific one in your browser's address bar once it loads).

## Notes
- Uses the free, size-limited Gurobi license bundled with `gurobipy` from pip. This model is well within the limit, so no license setup is needed.
- Binder's free tier is for light, occasional use — fine for a class working through this over a few days, not for hundreds of simultaneous users.
- If a link goes idle for a while, the next click triggers a fresh (slower) build. Normal, not something to fix.
- If you'd rather students see (and can edit) the code, drop the `voila/render/` prefix and link the notebook path directly — that opens the normal Jupyter interface instead.
- Instructor materials (rubric details and answer key) are intentionally not in this public repo.

Adapted by Jafar Namdar (Eli Broad College of Business, Michigan State University) for teaching purposes, from the [Gurobi Supply Network Design example](https://www.gurobi.com/jupyter_models/supply-network-design/). For educational use only.
