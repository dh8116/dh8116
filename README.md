# Richael (dh8116)

**Richael (dh8116) is a Year 11 student in Auckland, New Zealand, who writes GPU kernels in Triton, fine-tunes and serves language models, and builds two AI products: Soulor and VNportal.**

Every week I publish one Triton kernel benchmarked against PyTorch, including the weeks it loses. I'm also leading a five-person research paper on verifier error in reinforcement learning with verifiable rewards (RLVR).

## Projects

- **[Soulor](https://soulor.app/)**: Soulor helps reading social situations with multiple perspectives, and helps users rehearse hard conversations by simulating others with analyses and suggestions, there are also companions that knows the full context if users choose to share that can chat with them naturally. It can be both serious and entertaining, by switching different world views, and it fully respects users' privacy by keeping all texts encrypted.
- **[VNportal](https://vnportal.vercel.app/)**: VNportal is a browser-based vinyl and music platform: find a record in the MusicBrainz database, play it, mix it on two decks, and create with AI music tools — no install, no hardware, no Spotify Premium.

## Kernel write-ups

Best so far: fused cross-entropy at **15.90 ms vs PyTorch's 24.03 ms** at vocab 131,072 (1.51x), with 1.67x less peak memory. [All write-ups →](https://dh8116.github.io/blog)

## Elsewhere

[dh8116.github.io](https://dh8116.github.io/) · [X @RicaV42](https://x.com/RicaV42) · huangd6666@gmail.com
