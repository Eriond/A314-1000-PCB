# A314-1000-PCB
A314 board for the A1000's front memory expansion bay

<p>This is the Amiga 1000 version of [the A314](https://github.com/niklasekstrom/a314), designed to fit in the front expansion bay of the iconic computer.<br>
It is built using readily available components and has been designed with the DIY builder in mind (ie. no BGA chips, and reasonably large components with external leads)</p>
<p>It is a 1:1 replacement for the A1050 C= memory expansion, and will provide 256kB of chipRAM regardless if the RPiZ module is present.<br>
The board has room for an optional RTC chip which can provide time and date to the RPiZ via an I2C bus. This bus has also been made available via solderpads and is accessible from both sides of the PCB. It can be useful if you'd like to add other peripherals, like RGB lights or an OLED display for instance.</p>

For more information on how to bring this hardware to life, please check out Niklas repository at [https://github.com/niklasekstrom/a314-1000-gateware](https://github.com/niklasekstrom/a314-1000-gateware)

![PCB](Images/A314-1000%20front.jpg?raw=true)
