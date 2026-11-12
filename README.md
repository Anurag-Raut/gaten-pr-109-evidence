# Gaten PR #109 device evidence

Screenshots and a screen recording captured on a physical **Motorola moto g35 5G**
(ZA222WGJPP, Android 15), from the debug APK built at head `2eb62c6` of
`Anurag-Raut/Gaten` (sha256 `d65b68698a4344f4ac1f97269f05eebd7af966f063b8642c63301fcba898d2d3`).

Screenshots `14`–`21` are the follow-up round: the shared Enhanced download
confirmation dialog, the approved Standard/Enhanced rows, and the confirm-first
row state. They were captured from the debug APK built from head `9d49e25`
(`app-arm64-v8a-debug.apk`, sha256
`bdc0aad9936098cee702bfcca8c8f78501acc8884e01f34fb870bb5ef8b4a179`).
`19` is the Settings row at the system's extra-extra-large text size; `20` and
`21` are the same rows and dialog in the app's Dark theme. `18` is the existing
Text recognition Help dialog on the same build, for design-language comparison.
`22` is a short screen recording of the Settings dialog: Download opens the
confirmation while the row keeps its Download button, and Cancel returns to the
unchanged row. `23` is that dialog at the system's extra-extra-large text size.

Kept outside the Gaten repository so nothing here is committed to it.
