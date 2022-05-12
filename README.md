1. fork this repository to your github account
2. to change your keymaps, go to `boards/arm/rable/rable.config` and commit after that
3. to enable RGB underglow, go to `boards/arm/rable/rable_defconfig`, change to `CONFIG_ZMK_RGB_UNDERGLOW=y` and `CONFIG_WS2812_STRIP=y`, commit after that
4. pay attention to Actions tab
5. click to download firmware once build is finished, extract it to get `zmk.uf2`
6. reset your PCB, short it with tweezer or click reset button twice, there will be `NRF52BOOT` on your explorer/finder
7. drag `zmk.uf2` to the removable disk drive
8. enjoy your rable!

thanks to alabahuy for making the PCB reality!
