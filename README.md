# Quantix AI — Official Models Catalog Hub

Official hosted model catalog for the **Quantix AI** desktop ecosystem.

- **Direct JSON Endpoint**: [models_catalog.json](models_catalog.json)
- **Host**: GitHub Pages (Fastly Global Edge CDN)
- **Deployment**: Automatic continuous deployment on commit to `main`

## Tier Definitions (4GB VRAM Step Scaling)
- **Tier 0**: CPU Fallback / Limited ($\le 2\text{ GB}$ VRAM)
- **Tier 1**: $2 - 4\text{ GB}$ VRAM (Edge & Lightweight models: Llama 3.2 1B/3B, Qwen 2.5 1.5B, Phi-3 Mini)
- **Tier 2**: $4 - 8\text{ GB}$ VRAM (Standard models: Llama 3.1 8B, Qwen 2.5 7B, Mistral 7B, DeepSeek R1 8B)
- **Tier 3**: $8 - 12\text{ GB}$ VRAM (Advanced models: Qwen 2.5 14B, DeepSeek Coder V2 16B)
- **Tier 4**: $12 - 16\text{ GB}$ VRAM (High-memory pro workstations)
- **Tier 5**: $16 - 20\text{ GB}$ VRAM (Heavyweight models: Qwen 2.5 32B)
- **Tier 6**: $20 - 24\text{ GB}$ VRAM (Top-tier single GPU: RTX 3090 / 4090)
- **Tier 7**: $24 - 28\text{ GB}$ VRAM (Multi-GPU / High VRAM enterprise)
- **Tier 8**: $28 - 32\text{ GB}$ VRAM (Dual-GPU enterprise workstations)
- **Tier 9**: $32 - 36\text{ GB}$ VRAM (Workstation cluster setups)
- **Tier 10**: $36 - 40+\text{ GB}$ VRAM (Flagship models: Llama 3.1 70B)
