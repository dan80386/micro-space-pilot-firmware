# Micro Space Pilot firmware

Released firmware for the Micro Space Pilot desk console.

A console with its home WiFi set up checks this repository's latest release
for new firmware (UTILITY › INTERNET). Each release carries two files:

| File | What it is |
|---|---|
| `firmware.bin` | the firmware image |
| `manifest.json` | the release's version, size, SHA-256 checksum, download link, date and notes |

The console installs a release only when its version is higher than its own
and the downloaded image matches the checksum in the manifest.
