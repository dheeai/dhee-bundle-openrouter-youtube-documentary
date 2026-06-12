# dhee-bundle-openrouter-youtube-documentary

> YouTube-style documentary videos for [Dhee](https://github.com/dheeai) — OpenRouter image/video generation + LLM script & narration.

A Dhee **bundle** (pipeline) providing the bundle id `openrouter_youtube_documentary`. Discovered via the `dhee-bundle-*` npm convention; referenced as `npm:dhee-bundle-openrouter-youtube-documentary#openrouter_youtube_documentary`.

## Requirements

- **Runners**: `llm.generate`, `ffmpeg.concat` (built into dhee-core), **`openrouter.image`** — install [`dhee-runner-openrouter-image`](https://github.com/dheeai/dhee-runner-openrouter-image) (declared under `dependencies.runnerPackages`) — and **`openrouter.video`** (an OpenRouter video runner; provide your own / not bundled).
- An **OpenRouter API key** in the environment for the image/video runners.

## Layout

```
bundles/openrouter_youtube_documentary/
  bundle.json     prompts/   schemas/
```

## License

MIT
