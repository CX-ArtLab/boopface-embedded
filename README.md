# BoopFace Embedded 0.1.0

Experimental C++11 robot eyes. Import this ZIP with Arduino IDE's
Sketch → Include Library → Add .ZIP Library. Examples appear under
File → Examples → BoopFace. SerialEyes needs no screen;
OledSSD1306 needs the Adafruit SSD1306 library and a 128×64 I²C OLED.

All board configurations compile in CI; physical verification is pending.

- Guide and firmware examples: https://github.com/CX-ArtLab/boopface/tree/main/embedded
- Simulator: https://cx-artlab.github.io/boopface/hardware/
- Issues: https://github.com/CX-ArtLab/boopface/issues

Use #include <BoopFace.h> and boopface::Eyes. The caller supplies the
framebuffer, clock and display driver. No Arduino dependency in the core.

Arduino Library Manager and PlatformIO listings will follow; install from ZIP
or source until they are available. License: MIT (see LICENSE).
