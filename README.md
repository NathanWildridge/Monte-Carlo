# Gambler's Ruin & Random Walk Simulation

Exploring the gambler's ruin problem: simulating symmetric and biased
random walks with absorbing boundaries, and comparing empirical results
against closed-form theory.

## Progress

- [x] Symmetric random walk with absorbing boundaries (±b), estimate
      hitting probabilities and hitting times
- [ ] Compare simulated hitting probability/time vs. theoretical
      (P = 0.5, E[T] = b²)
- [ ] Extend to biased walk (gambler's ruin proper), vary p, compare
      to closed-form ruin probability
- [ ] Convergence analysis: simulated probability vs. theoretical as
      n increases, with Monte Carlo standard error
- [ ] Scale to Brownian motion limit (step size ∝ √Δt, many steps)
- [ ] Monte Carlo option pricing under GBM vs. Black-Scholes closed form
