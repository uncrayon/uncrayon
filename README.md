I build local AI systems and scientific software, focusing on inference efficiency, evaluation, and research grounded in working systems.

## Selected projects

### [KVPark](https://github.com/uncrayon/kvpark)

Save and restore local-model inference state, with Hermes and OpenCode integrations.

- **State persistence:** disk save/resume using a managed patched llama.cpp runtime, a single slot, and a compatible model/build. The agent keeps the transcript.
- **Experimental cross-model transfer:** translate caches through a shared latent so another model can reuse part of a conversation. Quality varies by model and workload, especially for long documents and tool-heavy agent work.

[Validation and scope](https://github.com/uncrayon/kvpark/blob/main/docs/validation.md) · [Experimental bridge](https://github.com/uncrayon/kvpark/blob/main/docs/bridge.md)

### [open-vidqc](https://github.com/uncrayon/open-vidqc)

A video-quality evaluation prototype combining OCR, temporal features, and XGBoost to detect text inconsistencies and flicker, with frame-level evidence, a CLI, and Docker packaging.

Published evaluation uses a small synthetic dataset; broader real-video validation remains open. Source-available under PolyForm Noncommercial.

### [Separatrix](https://github.com/uncrayon/separatrix)

A Rust, React, TypeScript, and Tauri desktop app for exploring dynamical systems, including phase portraits, bifurcations, and Lyapunov spectra. Available for Windows, macOS, and Linux.

## Teaching and competitions

- Over eight years teaching applied mathematics for biology and complex systems at **UNAM's Faculty of Sciences**.
- Instructor of the [NemoClaw course](https://platzi.com/nemoclaw/).
- **Solo silver medal** in Kaggle's RSNA Knee Abnormality Detection competition: **103rd of 6,299 teams, top 1.64%**. [Competition profile](https://www.kaggle.com/ulisesrayon/competitions)

## Systems debugging

[HIP top-k investigation in llama.cpp](https://github.com/ggml-org/llama.cpp/pull/27974): investigated CPU fallback on AMD hardware and proposed a hipCUB path. The PR was closed as a duplicate; measurements showed no material throughput gain.

## Contact

[uliarp15@gmail.com](mailto:uliarp15@gmail.com)
