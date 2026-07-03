# Methodology

## Synthetic Simulation

The synthetic model represents an online information environment as a graph.

- Nodes represent users.
- Edges represent possible information transmission paths.
- Communities represent echo chambers.
- Bridge edges connect different communities.
- Influencer nodes have a stronger role in spreading information.

The model uses three states:

- `S` — susceptible user;
- `F` — user exposed to claim-like or fake-like content;
- `C` — user exposed to fact-checking content.

## Monte Carlo Simulation

Monte Carlo simulations are used to estimate:

- final fake-like reach;
- outbreak probability;
- effectiveness of fact-checking strategies;
- sensitivity to spreading probability;
- sensitivity to fact-checking strength;
- influence of bridge links;
- influence of fact-checking delay.

## Empirical Validation

The empirical part uses the Hoaxy dataset.

Main steps:

1. Download and preprocess Hoaxy data.
2. Build a retweet network.
3. Detect communities.
4. Classify edges as bridge or intra-community.
5. Analyze centrality and k-core structure.
6. Estimate empirical percolation threshold.
7. Compare targeted and random intervention strategies.
8. Analyze whether centrality predicts future claim-like activity.

## Limitations

- Real social media behavior is more complex than a simplified graph model.
- Claim-like content should not automatically be interpreted as legally proven misinformation.
- The model is intended for research and exploratory analysis.
