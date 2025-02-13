# ABM-fake-news
This repository contains an Agent-Based Model (ABM) designed to simulate the spread of fake news and misinformation within a networked population. The model explores how beliefs evolve over time, the impact of trolls, and the effectiveness of various countermeasures to mitigate misinformation.

## Model Overview
The ABM simulates a population of agents on a grid, where each agent holds a belief ranging from -1 (fake news) to 1 (fact-checked news). Agents influence each other based on their convincing power and interactions within their neighborhood. The model introduces trolls—agents with fixed negative beliefs—to study their impact on misinformation spread.

### Key Parameters:
- Population Size (N): Number of agents in the simulation.

- Convincing Power (c<sub>i</sub>): An agent's ability to influence others.

- Initial Belief Fraction (p<sub>+</sub>): Fraction of agents initially supporting fact-checked news.

- Troll Fraction (f<sub>troll</sub>): Proportion of trolls in the population.
