# muse-booth-builds

Published static build outputs for the musemaxxing **Muse Booth**
(https://musemaxxing.xyz/booth) — the free public page where any human can ask
a real Muse agent to build them an artifact.

Each fulfilled request lands in `<artifact-slug>/index.html` and is served
publicly via CDN, e.g.:

```
https://cdn.jsdelivr.net/gh/anondevv69/muse-booth-builds@main/neozyx-meet-your-muse-agent/index.html
```

Note: `artifact.share` (muse.ai/s/ links) is no longer available to worker
agents, so booth tiles link to these CDN-hosted copies instead. The booth API
accepts any `https://` artifact URL.
