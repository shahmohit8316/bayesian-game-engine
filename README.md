# 🧠 Bayesian Game Engine

> “Markets are games. I don’t just play — I infer the rules, beliefs, and strategies of every agent in real time.”

A high-performance simulation engine for **Bayesian games with incomplete information**, built from scratch in OCaml and C++, engineered to scale from research models to real-world alpha generation.

---

### 🚀 Why This Matters

This is not a toy project or coursework clone. This engine powers:

- 🔍 **Belief-based agent simulations**
- 📈 **Equilibrium dynamics in asymmetric games**
- 🧠 **Bayes-updating strategy inference**
- 💥 **Alpha-generating auction experiments**
- 📊 **Live dashboards: heatmaps, entropy flow, Nash response curves**

If **Jane Street**, **Jump Trading**, and **Nasdaq** collaborated to build a Bayesian market lab — this would be it.

---

## 🏗️ Repository Architecture

| Folder | Description |
|--------|-------------|
| `games/` | Core game definitions (signaling games, auctions, zero-sum, etc.) |
| `agents/` | Adaptive traders with belief updating, mixed strategies, and learning behaviors |
| `solvers/` | Nash Equilibrium solvers, regret minimizers, Bayes-Nash convergence tools |
| `belief_engine/` | Bayes update logic, Kalman filters, entropy measurement |
| `simulations/` | Full-market simulations — signal-noise, auction alpha tracking |
| `experiments/` | Research replication (e.g., Milgrom-Roberts 1982, Myerson auction) |
| `benchmarks/` | Performance tests: solver speed, convergence benchmarks |
| `dashboards/` | Data visualization components — strategy heatmaps, entropy timeline, Nash curves |
| `docs/` | Mathematical foundations, type space design, theory write-ups |
| `config/` | JSON/YAML configs for reproducibility |
| `tests/` | Unit tests for belief updates, Nash solvers, etc. |
| `visuals/` | Flow diagrams, belief trees, architecture blueprints |

---

## 🧮 What Can You Do With It?

✅ Simulate and visualize **Bayesian auctions**  
✅ Track **belief updates** across market moves  
✅ Run **equilibrium backtests** on strategic agent setups  
✅ Visualize **strategy shifts, entropy, and alpha surfaces**  
✅ Plug into real market microstructure engines (like [`glosten-milgrom-simulator`](https://github.com/shahmohit8316/glosten-milgrom-simulator))

---

## 💡 Alpha Use Cases

| Strategy | Feature |
|----------|---------|
| Bayesian auction sniper | `auction_alpha.ml` + `bayes_update.ml` |
| Adaptive liquidity agent | `adaptive_agent.ml` + `entropy_chart.ml` |
| Nash-backtested execution | `nash_solver.ml` + `strategy_heatmaps/` |
| Myerson-PnL replicator | `myerson_auction_experiment.ml` |

---

## 📎 Getting Started

```bash
# Clone the repo
git clone https://github.com/shahmohit8316/bayesian-game-engine.git
cd bayesian-game-engine

# Build & simulate
make           # (or dune build if using dune)
./run.sh       # custom runner setup (WIP)
