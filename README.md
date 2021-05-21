[![info](https://img.shields.io/badge/ARM-Platform-blue)](https://developer.arm.com/documentation)
[![info](https://img.shields.io/badge/NXP-Kinetis-orange)](https://www.nxp.com/products/processors-and-microcontrollers/arm-microcontrollers/general-purpose-mcus/k-series-cortex-m4:KINETIS_K_SERIES)
[![info](https://img.shields.io/badge/NXP-LPC-yellowgreen)](https://www.nxp.com/products/processors-and-microcontrollers/arm-microcontrollers/general-purpose-mcus/lpc800-cortex-m0-plus-:MC_71785)
# NXPduino
Arduino for NXP Kinetis and LPC platforms.

Intention of this project is to provide an Arduino like entry to NXP CPUs.
User will have access to a plenty of existing libraries with many boards on the market.
Once Arduino will no more fullfill user's needs, [MCU Expresso](https://www.nxp.com/design/software/development-software/mcuxpresso-software-and-tools-/mcuxpresso-integrated-development-environment-ide:MCUXpresso-IDE), [MBED](https://os.mbed.com/), [Zephyr](https://zephyrproject.org/) or [PlatformIO](https://platformio.org/) can be a way to get more.

Enthusiasts, UI / UX designers and testers are welcome.

- [ ] We plan to start with [FRDM-K64F](#frdm-k64-board) and [LPC845-BRK](#lpc845-brk-board) boards,
- [ ] reuse [MCU boot](https://github.com/mcu-tools/mcuboot) to stay compatible with other development approaches,
- [ ] and maybe we will finally plug result also into the [PlatformIO](https://platformio.org/) IDE.

## Boards
<a id="frdm-k64-board"></a>
- [FRDM-K64F](https://www.nxp.com/design/development-boards/freedom-development-boards/mcu-boards/freedom-development-platform-for-kinetis-k64-k63-and-k24-mcus:FRDM-K64F)

<img src="/docs/images/frdm_k64f.jpg" width="400px" alt="frdm-k64f board">&nbsp;&nbsp;&nbsp;<img src="/docs/images/frdm_k64f_reve4_header_pinout.jpg" width="400px" alt="frdm-k64f pinout">

<a id="lpc845-brk-board"></a>
- [LPC845-BRK](https://www.nxp.com/products/processors-and-microcontrollers/arm-microcontrollers/general-purpose-mcus/lpc800-cortex-m0-plus-/lpc845-breakout-board-for-lpc84x-family-mcus:LPC845-BRK)

<img src="/docs/images/LPC845-BRK-1.webp" width="500px" alt="lpc845-brk board"><img src="/docs/images/LPC845-BRK-BD2.webp" width="300px" alt="lpc845-brk pinout">

## Bootloader
<!--- <details>
   <summary>Click to expand.</summary> --->
- MCU Boot
<!--- </details> --->

## Integration
- Arduino IDE
- PlatformIO
