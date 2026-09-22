# Network Rescue: The UK Distribution Challenge

A supply chain network design game for senior undergraduate Supply Chain Management students.
Teams act as consultants, analyze an optimization model of a UK distribution network,
stress-test it, audit it, and present a strategic recommendation to "the board."

Adapted by **Jafar Namdar** (Eli Broad College of Business, Michigan State University) for teaching purposes,
from the [Gurobi Supply Network Design example](https://www.gurobi.com/jupyter_models/supply-network-design/).
For educational use only.

## ▶️ Launch the game (no installation needed)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/USERNAME/REPO/HEAD?labpath=Network_Rescue_Game_student.ipynb)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/USERNAME/REPO/blob/main/Network_Rescue_Game_student.ipynb)

Click either badge. Binder can take 1–3 minutes to start the first time.

## How to play

1. Open the notebook and read **Part 1 — Briefing Book**.
2. Run the two cells in **Part 2 — Launch the Model**. A control panel appears.
3. Adjust the panels, click **Solve with Gurobi**, and answer the questions round by round.
4. To reset to the baseline, re-run the second cell in Part 2.

## ⚠️ Save your work — Binder does not

Binder sessions are temporary. They shut down after about 10 minutes of inactivity and **all changes are lost**.

- Save often with **File → Download** (downloads your `.ipynb`).
- To continue later, relaunch Binder and upload your saved notebook (drag it into the file browser).
- Prefer Colab if you want your work saved automatically to Google Drive (**File → Save a copy in Drive**).

## Technical notes

- Uses the free, size-limited Gurobi license bundled with `gurobipy` from pip. This model is well within the limit, so no license setup is needed.
- Dependencies are listed in `requirements.txt`; Binder installs them automatically.
