---
title: "AI for Durak Using a Partially Observable Markov Decision Process"
excerpt: "A hybrid AI using expertly crafted heruistics for early game Durak playing and Monte Carlo Tree Search on sampled states for endgame decision-making."
collection: portfolio
---

[GitHub](https://github.com/larsenbier/Durak-Endgame-Monte-Carlo-Tree-Search)

I present an AI to play the popular variant of Durak known as Perevodnoy Durak. The AI is based on two decision-making components: one for the early game where the belief state is extremely large and samples have high variance, and one for the endgame where the agent can combine all the information it has seen throughout the game to focus on a few plausible states for the game to be in. The project includes a fully implemented version of the AI, along with a playable version that one can play against. A brief analysis of the AI's effectiveness compared to other methods is included.
