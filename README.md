# NXPduino
Arduino for NXP Kinetis and LPC platforms.

Intention of this project is to provide an Arduino like entry to NXP CPUs.
User will have access to a plenty of existing libraries with many boards on the market.
Once Arduino will no more fullfill user's needs, [MCU Expresso](https://www.nxp.com/design/software/development-software/mcuxpresso-software-and-tools-/mcuxpresso-integrated-development-environment-ide:MCUXpresso-IDE), [MBED](https://os.mbed.com/), [Zephyr](https://zephyrproject.org/) or [PlatformIO](https://platformio.org/) can be a way to get more.

Enthusiasts, UI / UX designers and testers are welcome.

- [ ] We plan to start with [FRDM-K64F](#boards) and [LPC845-BRK](#boards) boards.
- [ ] Reuse [MCU boot](https://github.com/mcu-tools/mcuboot) to stay compatible with other development approaches.
- [ ] Maybe we will finally plug result also into the [PlatformIO](https://platformio.org/).

## Boards
- [FRDM-K64F](https://www.nxp.com/design/development-boards/freedom-development-boards/mcu-boards/freedom-development-platform-for-kinetis-k64-k63-and-k24-mcus:FRDM-K64F)

<img src="/docs/images/frdm_k64f.jpg" width="400px" alt="frdm-k64f board">
<img src="/docs/images/frdm_k64f_reve4_header_pinout.jpg" width="400px" alt="frdm-k64f pinout">

- [LPC845-BRK](https://www.nxp.com/products/processors-and-microcontrollers/arm-microcontrollers/general-purpose-mcus/lpc800-cortex-m0-plus-/lpc845-breakout-board-for-lpc84x-family-mcus:LPC845-BRK)

<img src="/docs/images/LPC845-BRK-1.webp" width="500px" alt="lpc845-brk board">
<img src="/docs/images/LPC845-BRK-BD2.webp" width="450px" alt="lpc845-brk pinout">

## Bootloader
<!--- <details>
   <summary>Click to expand.</summary> --->
- MCU Boot
<!--- </details> --->

## Integration
- Arduino IDE
- PlatformIO
