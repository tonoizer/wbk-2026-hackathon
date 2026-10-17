# Temporary Cloudflare migration inputs

These reviewed patches contain the Cloudflare hosting changes for the original
Beierthon repositories. They are stored here because the current GitHub
integration cannot write to Beierthon. Production source ownership remains with
Beierthon. Deployments must verify both the original main commit and the patch
SHA-256 before applying a patch; no unpinned patch or third-party script is used.

2025 base: c078b887b8ab6f1a4fb7b7d0c5590978bb3dc250.
2026 base: bcd81199c07cf95c8fce2219062aa2459ce31971.

Use these inputs only to bootstrap the hosting migration. Merge the equivalent
changes into the original repositories when their GitHub write access is fixed,
then replace the temporary build commands with the normal checked-in scripts.
No credentials, R2 bindings or paid-service setup are included.
