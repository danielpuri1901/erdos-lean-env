# erdos-lean-env

Prebuilt Lean dependencies for cloud sessions of a private formalization project.

The release assets hold `.lake/packages` after `lake build Env`: formal-conjectures at commit `df3f12d7bd06feb3f71ae37abae0ca7cb798d9b1`, Mathlib `v4.33.1`, and their dependencies, compiled with Lean `v4.33.1` installed at `/opt/lean`.
All of them are open-source (formal-conjectures and Mathlib are Apache-2.0).
This repository holds no proofs and no project code, only the pins in `lakefile.toml` and `lake-manifest.json` and the workflow that builds the assets.

Rebuild: run the `build-env` workflow with a new tag.
