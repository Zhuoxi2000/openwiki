---
"openwiki": patch
---

Stamp internal links whose heading anchor contains a malformed percent escape (e.g. `#100%-coverage`) as broken instead of throwing `URIError` and failing wiki finalization.
