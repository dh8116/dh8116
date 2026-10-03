# Richael (dh8116)

**Richael (dh8116) is a Year 11 student in Auckland, New Zealand, who writes GPU kernels in Triton, fine-tunes and serves language models, and builds two AI products: Soulor AI and VNportal.**

Every week I publish one Triton kernel benchmarked against PyTorch, including the weeks it loses. I'm also leading a five-person research paper on verifier error in reinforcement learning with verifiable rewards (RLVR).

## Projects

- **[Soulor AI](https://soulor-ai.vercel.app/)**: Soulor AI is an AI companion app with persistent memory and five relationship stages, from Stranger to Soulmate, plus a Simulation Mode that gives a panel of five AI perspectives on any situation. It runs on its own LoRA fine-tune of Qwen3-14B, served with vLLM on Modal.
- **[VNportal](https://vnportal.vercel.app/)**: VNportal is a browser-based vinyl and music platform: find a record in the MusicBrainz database, play it, mix it on two decks, and create with AI music tools — no install, no hardware, no Spotify Premium.

## Kernel write-ups

Best so far: fused cross-entropy at **15.90 ms vs PyTorch's 24.03 ms** at vocab 131,072 (1.51x), with 1.67x less peak memory. [All write-ups →](https://dh8116.github.io/blog)

## Elsewhere

[dh8116.github.io](https://dh8116.github.io/) · [X @RicaV42](https://x.com/RicaV42) · huangd6666@gmail.com
