# OTA feed: LineageOS for the Samsung Galaxy Z Fold6 (q6q)

Unofficial LineageOS builds, maintained by [mojoaj](https://github.com/mojoaj).

- The built-in Updater app (Settings > System > Updater) reads one feed per LineageOS version:
  - `q6q-24.0.json`: LineageOS 24.0 (Android 17), current
  - `q6q.json`: LineageOS 23.2 (Android 16), no longer updated
- 23.2 users are not offered 24.0 automatically: sideload the 24.0 zip (plus MindTheGapps 17 if you use GApps) to upgrade.
- Downloads (OTA zip, Odin recovery `.tar.md5`, SHA256SUMS) are on the [Releases](https://github.com/mojoaj/lineage_q6q_ota/releases) page.
- Source: [android_local_manifests_q6q](https://github.com/mojoaj/android_local_manifests_q6q) (branch `q6q-24.0` for 24.0, `q6q` for 23.2).
- Report bugs: [device tree issues](https://github.com/mojoaj/android_device_samsung_q6q/issues).

Supported: SM-F956B only, on F956BXXS2BYGB firmware (bootloader revision 2). Never flash Samsung firmware with bootloader revision 3 or higher: it permanently removes OEM unlocking.
