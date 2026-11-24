# VDS4E Host Adapters

Official host adapters translating standard Linux userspace ABIs into Unix-socket data-plane transactions for VDS4E:

- `spi-cuse`: SPI master adapter providing `/dev/spidevX.Y`
- `i2c-cuse`: I2C master adapter providing `/dev/i2c-X`
- `gpio-cuse`: GPIO chip adapter providing `/dev/gpiochipX` (libgpiod)
- `uart-pty`: UART serial adapter providing `/dev/pts/N` (termios)
- `ethernet-tap`: Ethernet network adapter providing TAP interface `vdsN`
