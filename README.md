# Hafiz CDN

Static public assets for the Hafiz iOS app.

This repository intentionally contains no application source code. It is used as
a jsDelivr-backed CDN for downloadable Mushaf page images.

Current production path:

```text
https://cdn.jsdelivr.net/gh/abbosoktambayev/hafiz-cdn@main/mushaf-cdn/png/r4/
```

Keep old revision folders when possible. Older app builds may still request
their original revision path.
