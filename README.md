# NIL — Visual Inspector

**Live docs:** https://www.neuromorphicinference.com/demos/visual-inspector  
**Evidence index:** https://www.neuromorphicinference.com/evidence  

## Goal
Image classification with explainability and production-oriented inference packaging (CPU-first, GPU optional).

## What it will include
- Upload image → prediction + confidence
- Explainability view (e.g., Grad-CAM-like heatmap)
- Regression tests on a dataset snapshot (prevent silent degradation)
- Clear latency/model-size trade-offs + “inference notes”

## Framework choice
Primary: **PyTorch** (recommended).  
Optional: use **TensorFlow** in exactly one module if needed (to avoid “ATS listing” without substance).

## Status
Planned → in progress

## Roadmap
1) Minimal inference service + simple UI
2) Add explainability + failure cases gallery
3) Add test suite + packaging + performance notes
