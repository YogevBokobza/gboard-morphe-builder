# Gboard Morphe builder

Builds a non-root Gboard APK patched with
[jasonwu1994/Gboard-patches](https://github.com/jasonwu1994/Gboard-patches)
and publishes it as a GitHub release.

- The CI workflow runs daily and builds only when a new patches release is out.
- Output: `gboard-patches-v<version>-arm64-v8a.apk`.
- The default "Package Rename" patch installs it as
  `dev.jason.com.google.android.inputmethod.latin`, next to the stock Gboard.
- Releases are tracked by [youtube-updater](https://github.com/YogevBokobza/youtube-updater).

Based on [j-hc/revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)
(GPL-3.0). See `CONFIG.md` for config options.
