# NHL Injuries Are Up — Or Are They?

A Bayesian analysis of whether the 2025/26 NHL season is experiencing an unusual injury surge, or whether early coverage was overreading random noise.

📖 [Full writeup](https://chrishires.com/posts/nhl-injuries/)

**Methods:** Hierarchical Poisson model with a Gamma prior on season-level injury rates, fit via MCMC using PyMC. The historical posterior is repurposed as a prior for the in-progress 2025/26 season, enabling a full-season rate estimate from partial data.

**Setup:** `pip install pymc arviz pandas numpy matplotlib jupyter`