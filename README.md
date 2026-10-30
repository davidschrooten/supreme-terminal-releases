# Supreme Terminal releases

Signed release builds of Supreme Terminal, an SSH client for Android phones and tablets. This repository only holds releases; each one is published here automatically when a version is tagged.

No release has been published yet.

## Install

Download `supreme-terminal-v<version>.apk` from the [latest release](../../releases/latest) and sideload it, for example:

```bash
adb install -r supreme-terminal-v<version>.apk
```

Check the download against the release's `SHA256SUMS`.

## For tools

Every release carries `latest.json`, at the stable URL `https://github.com/davidschrooten/supreme-terminal-releases/releases/latest/download/latest.json`:

```json
{
  "versionName": "1.0.0",
  "versionCode": 1000000,
  "apkUrl": "https://github.com/davidschrooten/supreme-terminal-releases/releases/download/v1.0.0/supreme-terminal-v1.0.0.apk",
  "sha256": "…",
  "notes": "…",
  "publishedAt": "…"
}
```

## Licence

Apache-2.0. See [LICENSE](LICENSE).
