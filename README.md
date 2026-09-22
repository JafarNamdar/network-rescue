# Network Rescue: The UK Distribution Challenge

A supply chain network design game for senior undergraduate Supply Chain Management students.
Teams act as consultants, analyze an optimization model of a UK distribution network,
test it against disruptions and demand uncertainty, and recommend strategies in a 7–8 minute presentation.

Adapted by **Jafar Namdar** (Eli Broad College of Business, Michigan State University) for teaching purposes,
from the [Gurobi Supply Network Design example](https://www.gurobi.com/jupyter_models/supply-network-design/).
For educational use only.

## 🎮 Play the game

The game runs in two modes. Use **Work mode** for the assignment.

**Work mode — full notebook (type your answers here):** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/JafarNamdar/network-rescue/HEAD?labpath=Network_Rescue_Game_student.ipynb)

**Simulator mode — code-free control panel (Voila):** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/JafarNamdar/network-rescue/HEAD?urlpath=voila%2Frender%2FNetwork_Rescue_Game_student.ipynb)

If the badges don't render on your device, use these direct links:

- Work mode: https://mybinder.org/v2/gh/JafarNamdar/network-rescue/HEAD?labpath=Network_Rescue_Game_student.ipynb
- Simulator mode: https://mybinder.org/v2/gh/JafarNamdar/network-rescue/HEAD?urlpath=voila%2Frender%2FNetwork_Rescue_Game_student.ipynb
- Colab (saves to your Google Drive): https://colab.research.google.com/github/JafarNamdar/network-rescue/blob/main/Network_Rescue_Game_student.ipynb

First click can take 2–5 minutes to build (it's setting up a private Python environment with the Gurobi optimizer just for you). That's normal, just wait. After that it usually loads in about a minute.

### Which mode should I use?

| | Work mode (Jupyter) | Simulator mode (Voila) |
|---|---|---|
| Shows the briefing, questions, and control panel | ✅ | ✅ |
| Shows Python code | ✅ | ❌ |
| Type answers into the notebook | ✅ | ❌ |
| Best for | Completing and submitting the assignment | Quickly running what-if scenarios in class or during your presentation |

## How to play (Work mode)

1. Read **Your mission** and **Key terms** at the top.
2. Run the two code cells under **Launch the Model** (click a cell, then **Shift + Enter**). A control panel appears.
3. Expand the panels, change the values a question asks for, and click **Solve with Gurobi**.
4. To reset to the baseline, re-run the second code cell (in Simulator mode, refresh the page).
5. Type your answers in the ✏️ cells under each question and fill in the tables.

## ⚠️ Save your work — Binder does not

Binder sessions are temporary. They shut down after about 10 minutes of inactivity and **all changes are lost**.

- Save often with **File → Download** (downloads your `.ipynb`).
- To continue later, relaunch Work mode and drag your saved notebook into the file browser on the left.
- Prefer Colab if you want your work saved automatically (**File → Save a copy in Drive**).

## Notes for the instructor

- Uses the free, size-limited Gurobi license bundled with `gurobipy` from pip. This model is well within the limit, so no license setup is needed.
- Binder's free tier is meant for light use: fine for a class over a few days, not for hundreds of simultaneous users.
- Instructor materials (rubric and answer key) are intentionally **not** in this public repo.
