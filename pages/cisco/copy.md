# copy

> For Cisco network device

`copy running-config startup-config`

- Save the current configuration

`copy tftp://10.1.1.1/cisco/c7200-js-mz flash:`

- Copy an IOS image from TFTP server to flash

`copy current tftp://10.1.1.1/cisco/c7200-js-mz`

- Copy current configuration to a TFTP server

`copy xmodem: flash:`

- Copy an IOS image from console to flash(extremly slow!)
