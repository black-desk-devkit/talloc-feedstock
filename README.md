# talloc-feedstock

Conda feedstock for [talloc](https://talloc.samba.org/).

Builds the shared library, headers, and pkg-config metadata for
`linux-64` and `osx-arm64`.

## Update procedure

1. Bump `version` in `recipe/recipe.yaml`
2. Update the source `sha256`
3. Reset `build.number` to `0` on version bumps
4. Commit to `main` — CI builds and uploads to
   [prefix.dev/black-desk](https://prefix.dev/black-desk)
