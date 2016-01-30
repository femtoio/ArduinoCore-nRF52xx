# ArduinoCore-nRF52xx
Open Source Arduino core for the Nordic nRF52832. Depends on the Nordic nRF52 SDK (See `Nordic_files/` directory)

To set up your development environment, see https://devzone.nordicsemi.com/tutorials/7/

On Ubuntu, I had to set `GNU_INSTALL_ROOT` in Makefile.posix to `/usr`, as the arm-none-eabi-* toolchain was installed to `/usr/bin/`