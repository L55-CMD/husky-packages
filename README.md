# husky-packages

Release-asset hosting for the [Ubuntu Touch Pixel 8 Pro (husky) port](https://github.com/l55-cmd/device-google-husky).
Not a code repo - the releases here act as the "package registry":

- `main` release: base packages (`system.img.zip`, `libhybris-16-update.tar.xz`,
  mirrored LineageOS zip). Device CI falls back to this release for any branch.
- `<branch>` releases: `kernel.zip` built by the
  [lineage-kernel-manifest-husky](https://github.com/l55-cmd/lineage-kernel-manifest-husky) CI.
