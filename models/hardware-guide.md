# Hardware guide

Choose a model that leaves enough resources for the operating system, runtime, context, and agent tools.

| Device situation | Good starting point |
|---|---|
| CPU only | small, quantized models; expect lower speed |
| 8 GB system memory | small models with conservative context |
| 16 GB system memory | small to medium quantized models |
| 32 GB+ system memory | larger quantized models become practical |
| 8 GB GPU VRAM | small models or aggressive quantization |
| 12–16 GB GPU VRAM | many small/medium models |
| 24 GB+ GPU VRAM | larger models and longer contexts become more practical |
| Apple Silicon unified memory | model size competes with the OS and applications for shared memory |

These are starting points, not guarantees. Runtime, quantization, context length, architecture, and GPU offloading change actual requirements.

## Before downloading a model

1. Check model size on disk.
2. Check required RAM/VRAM for the chosen quantization.
3. Leave headroom for context and the runtime.
4. Check whether the runtime supports the model architecture.
5. Start with a smaller model and increase size only if the task needs it.
