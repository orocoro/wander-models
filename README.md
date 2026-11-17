# wander-models

Model files that the Wander iOS app downloads. Each model is a GitHub release; the app pins
every file by size and SHA-256, so release assets are never replaced, only added under a new tag.

## da3-metric-large-f16-v1 — Depth Anything 3 Metric-Large, Core ML F16

Licence: Apache-2.0 (see `LICENSE` and `NOTICE`). The upstream model is by ByteDance Seed.

The app rebuilds `DA3MetricLargeF16.mlpackage` from these assets:

| Release asset | Path in the package | Bytes | SHA-256 |
|---|---|---:|---|
| `DA3MetricLargeF16-Manifest.json` | `Manifest.json` | 617 | `d57221dede6250ea3f71c09e1d1e0ea5e807a4668158b4d226d4be3245fb53ce` |
| `DA3MetricLargeF16-model.mlmodel` | `Data/com.apple.CoreML/model.mlmodel` | 302,993 | `6f8a2aed32812528ffe9dbfbaefed7a17e295f74f8b369475b9466a3ce993481` |
| `DA3MetricLargeF16-weight.bin` | `Data/com.apple.CoreML/weights/weight.bin` | 667,555,648 | `6cb2ce1ba6632e18a3b545010f802b36e7b8a283d8c745bafad8ba99375b2c06` |
