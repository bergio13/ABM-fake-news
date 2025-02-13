# ABM-fake-news
This repository contains an Agent-Based Model (ABM) designed to simulate the spread of fake news and misinformation within a networked population. The model explores how beliefs evolve over time, the impact of trolls, and the effectiveness of various countermeasures to mitigate misinformation.

## Model Overview
The ABM simulates a population of agents on a grid, where each agent holds a belief ranging from -1 (fake news) to 1 (fact-checked news). Agents influence each other based on their convincing power and interactions within their neighborhood. The model introduces trolls—agents with fixed negative beliefs—to study their impact on misinformation spread.

### Key Parameters:
- Population Size (N): Number of agents in the simulation.

- Convincing Power (c<sub>i</sub>): An agent's ability to influence others.

- Initial Belief Fraction (p<sub>+</sub>): Fraction of agents initially supporting fact-checked news.

- Troll Fraction (f<sub>troll</sub>): Proportion of trolls in the population.

## Key Features
- Belief Dynamics: Agents update their beliefs based on interactions with neighbors.

- Trolls: Agents with fixed negative beliefs actively spread misinformation.

- Countermeasures:

  - Trusted Agents: Credible sources with high convincing power.

  - Reporting & Shadow Banning: Users can report trolls, reducing their influence.

  - Community Notes: Fact-checking mechanism to correct misinformation.

- Observables:

  - Average Belief: Overall trend of the population's beliefs.

  - Fraction of Positive Belief: Proportion of agents supporting fact-checked news.

  - Belief Variance (Polarization): Degree of disagreement in beliefs.

## Simulation Results
The simulation explores various scenarios, including:

- The impact of trolls on belief dynamics.

- The effectiveness of different countermeasures.

- The role of neighborhood structure and initial parameters.

Key findings:

- A critical troll fraction (f<sub>troll</sub> ≈ 0.207) was identified, beyond which negative beliefs dominate.

- Trusted agents slow the spread of misinformation but are insufficient alone.

- Shadow banning and community notes significantly reduce troll influence and stabilize beliefs.

## Countermeasures
The model implements several strategies to combat misinformation:

- Trusted Agents: Credible sources with high convincing power.

- Reporting & Shadow Banning: Users report trolls, reducing their influence.

- Community Notes: Fact-checking mechanism to correct misinformation.

- Troll Influence Reduction: Trolls lose convincing power when contradicted by community notes.

