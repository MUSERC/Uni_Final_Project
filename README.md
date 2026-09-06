#  Game Level Retention & Difficulty Analysis Pipeline

> Analytical pipeline, statistical models, and academic manuscript source code for analyzing player retention and level difficulty dynamics in word puzzle games.

## Core Objective

The main goal of this project is to model how controllable level design features and linguistic attributes influence **player churn** and **progression pacing**.

We specifically focused on:
*   **Design Features:** Layout dimensions, board counts, and word intersections.
*   **Linguistic Attributes:** Word rarity and vocabulary repetition.

---

##  Key Empirical Discoveries From the Paper

Our econometric analysis revealed some counter-intuitive insights about why players stay in the game:

###  1. Pacing Volatility Beats Ease
Absolute difficulty is often statistically insignificant when it comes to mid-game churn. Instead, **Difficulty Volatility** (Mean Absolute Successive Deviation - MASD) is the real game-changer.
*   **The Metric:** MASD has a highly significant negative coefficient (Odds Ratio ~ 0.56).
*   **The Impact:** A "spike-and-cooldown" pacing wave **reduces player churn odds by 44%** compared to a flat, predictable progression. 

###  2. Cognitive Anchoring
Familiarity keeps players engaged. Introducing repeated vocabulary from recent levels creates a comforting familiarity loop for the player.
*   **The Impact:** This looping mechanism significantly mitigates frustration and drops statistical churn compared to levels relying entirely on novel, unseen words.

---
