# UEFN Materials

UEFN material editing & graph tools (2026) — create/duplicate materials & instances, edit graphs, flags, assign to meshes. Bundles Materials skill: always layout graphs (no stacked nodes), PBR + MF_ patterns, water recipes, publish validators.

Desktop plugin for [UEFN-Ducky](https://github.com/UEFN-Ducky/UEFN-Ducky) (`materials`).
Install or update from **Settings → Store** in the app — do not install from a zip by hand.

## Build

```bash
py scripts/build_zip.py
```

Writes `deploy/materials-1.0.16.ducky-plugin.zip` (scripts/ and deploy/ are not packed).
