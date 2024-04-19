---
"tauri-driver": patch:bug
---

Fixed an issue where tauri-driver passed an invalid `null` value to the Edge driver if `webviewOptions` was missing in the `tauri:options` capability.
