<div align="center">

<a href="#">
    <img src="./assets/Doki.png" alt="Doki logo" title="Doki logo" width=30%/>
</a>

# [Doki](#) Building Guide
</div>

<details open="open">
    <summary>Table of contents</summary>
    <ol>
        <li><a href="#how-it-works">How does this repository work?</a></li>
        <li><a href="#quick-guide">How can users get Doki without coding knowledge?</a></li>
        <li><a href="#local-build">How can developers / contributors build Doki locally?</a></li>
        <li><a href="#build-with-github-codespaces">How to build Doki with GitHub Codespaces (pre-installed environment)?</a></li>
        <li><a href="#license">License</a></li>
        <li><a href="#need-help">Need help ?</a></li>
    </ol>
</details>

## How it works

TODO

## Quick Guide

> [!TIP]
> Download the APK from the repository's Releases page on your phone and tap it to install.

> [!IMPORTANT]
> `check.yml` may trigger builds automatically when upstream changes are detected — check Releases or Actions artifacts for new APKs.

> [!CAUTION]
> You may need to allow "Install unknown apps" for your browser or file manager in your device settings before installing.

## Local build

If you prefer a local build:

```sh
./gradlew assembleRelease
```

> [!WARNING]
> Signed CI builds require secrets: `KEYSTORE_BASE64`, `KEYSTORE_PASSWORD`, `KEY_ALIAS`, `KEY_PASSWORD`.
> Maintainers: add these in your fork's Settings → Secrets and variables → Actions.

## Build with GitHub Codespaces

TODO

## License

[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)

<div align="left">

You may copy, distribute and modify the software as long as you track changes/dates in source files. Any modifications
to or software including (via compiler) GPL-licensed code must also be made available under the GPL along with build &
install instructions.

</div>

## Need help ?

Questions? Ask for one small expansion (enable Actions steps, screenshots, or exact artifact names).

