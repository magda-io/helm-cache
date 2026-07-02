# helm-cache

A cache repo containing pre-built Helm binaries, used as a fallback download
source for Magda's CI/CD pipeline when the official distribution endpoint is
temporarily unreachable.

Binaries are attached as assets to versioned GitHub Releases (e.g. `v3.13.2`),
matching the naming convention used by the official Helm distribution:

```
helm-v<version>-linux-<arch>.tar.gz
```

Checksums (`sha256sum`) for each asset are listed on the corresponding
release page.
