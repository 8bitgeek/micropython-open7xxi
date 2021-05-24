# micropython-open7xxi
Micropython BSP for WaveShare OpenzXXI

Add the contents of this repo to micropython/ports/stm32/boards/ folder

$ cd micropython/ports/stm32

$ export JTAG=olimex-tiny
--OR--
$ export JTAG=olimex-tiny
--OR--
$ export JTAG=stlink

$ boards/OPEN7XXI_C/make.sh start

$ boards/OPEN7XXI_C/make.sh flash
--OR--
$ boards/OPEN7XXI_C/make.sh debug
