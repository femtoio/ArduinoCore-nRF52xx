# ArduinoCore-nRF52xx
Open Source Arduino core for the Nordic nRF52832. Depends on the Nordic nRF52 SDK (See `Nordic_files/` directory)

To set up your development environment, see https://devzone.nordicsemi.com/tutorials/7/

The Nordic nRF52 SDK archive is also available in `ArduinoCore-nRF52xx/Nordic_files` as `nRF52_SDK_0.9.2_dbc28c9.zip`

## Additional set up.
On Ubuntu, I had to set `GNU_INSTALL_ROOT` in `Nordic_files/components/toolchain/gcc/Makefile.posix` to `/usr`, as the arm-none-eabi-* toolchain was installed to `/usr/bin/`

On Mac OSX, I set `GNU_INSTALL_ROOT` in `Makefile.posix` to `/usr/local`

