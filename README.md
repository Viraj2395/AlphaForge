# AlphaForge

AlphaForge is an HFT-style trading simulator combined with a Reinforcement Learning agent.  
The project models realistic execution constraints such as fees, slippage, and latency, and trains an RL agent to make Buy / Sell / Hold decisions on short time horizons.

## Quickstart

```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\Activate.ps1
pip install -r requirements.txt
python -m src.env.smoke_sim
