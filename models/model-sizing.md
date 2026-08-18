# Model sizing

Use memory needs as a planning estimate, not an exact benchmark.

A rough weight-only estimate is:

`memory ≈ parameter_count × bytes_per_parameter`

Real use needs additional memory for the runtime, context/KV cache, temporary buffers, operating system, and agent tools.

Typical weight storage:

| Format | Approx. bytes/parameter | Use |
|---|---:|---|
| FP16/BF16 | 2 | higher quality, larger memory use |
| INT8 | 1 | reduced memory |
| 4-bit | 0.5 | common local inference option |
| 3-bit | 0.375 | smaller footprint, more quality tradeoff |

These are simplified estimates. Actual formats and runtime overhead vary.

## Practical rule

Leave headroom. A model that barely fits in RAM or VRAM may be slow, unstable, or leave too little memory for the context window and agent runtime.

For agent workloads, context and tool output can matter as much as model weights.
