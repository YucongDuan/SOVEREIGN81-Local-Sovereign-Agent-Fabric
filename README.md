# SOVEREIGN81 Local Sovereign Agent Fabric

Muse Glimmer, Qwen, Gemma, or any other local model is a replaceable **proposal engine**. The model never receives authority merely because it is local.

Pipeline: user intent and values → append-only DIKWP ledger → proposal → W-policy → one-action capability lease → shadow execution → real execution → reconciliation → rollback and understanding packet.

Quick start:

```bash
python -m venv .venv
source .venv/bin/activate
pip install -e .
sovereign81 demo --output demo_run
sovereign81 benchmark --output benchmark_run
```

Open `OPEN_DASHBOARD.html` offline. No model weights are included.
