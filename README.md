# pioarduino (p)eople (i)nitiated (o)ptimized (arduino)
# Fork of Platformio Espressif 32: development platform for [PlatformIO](https://platformio.org)

[![Build Status](https://github.com/pioarduino/platform-espressif32/workflows/Examples/badge.svg)](https://github.com/pioarduino/platform-espressif32/actions)

ESP32 is a series of low-cost, low-power system on a chip microcontrollers with integrated Wi-Fi and Bluetooth. ESP32 integrates an antenna switch, RF balun, power amplifier, low-noise receive amplifier, filters, and power management modules.

* [Documentation](https://docs.platformio.org/page/platforms/espressif32.html) (advanced usage, packages, boards, frameworks, etc.)

# Usage

1. [Install PlatformIO](https://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](https://docs.platformio.org/page/projectconf.html) file:

## Stable version
espressif Arduino 3.0.3 and IDF 5.1.4

See `platform` [documentation](https://docs.platformio.org/en/latest/projectconf/sections/env/options/platform/platform.html#projectconf-env-platform) for details.

```ini
[env:stable]
platform = https://github.com/pioarduino/platform-espressif32/releases/download/51.03.03/platform-espressif32.zip
board = ...
...
```

## Development version

```ini
[env:development]
platform = https://github.com/pioarduino/platform-espressif32.git#development
board = ...
...
```

# Configuration

Please navigate to [documentation](https://docs.platformio.org/page/platforms/espressif32.html).
