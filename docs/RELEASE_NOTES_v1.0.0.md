# Superfrog Arcade Edition — v1.0.0

**18 October 2026 · ESP32-P4 hardware-validated milestone**

- **DIRECT GAME:** boots straight into game Disc 1 with its own verified stage2, bypassing Story.
- **FULL STORY:** runs the original Story Disc with video and audio, then automatically resolves the change to game Disc 1.
- Makerstown arcade launcher with original menu graphics and the "System Boot Sequence" intro track.
- GPIO joystick and physical arcade controls, optimized low-latency audio (I2 4K), C1.39 video presenter.
- Both paths confirmed functional on the tested ESP32-P4 device.

## Known limitation

The PAL50 / ~25 fps presentation can lose some blink-phase fidelity for the main character. **Not fixed in this release.** Future fixes must not regress audio, latency or frame pacing.

## Future work

Investigate PAL sprite blinking, assess a distinct ESP32-S3 port, and evaluate USB gameplay capture in separate workstreams.

## Public distribution

This GitHub repository documents the milestone but does not include game disks, Amiga ROMs, disk-derived loader binaries, firmware with proprietary assets, or the source of the private universal porting engine.
