## Portlane.HODL - Bitcoin and Nyan Keys ⚡

### ABOUT ME
BitCoin maximalist and Bitcoin Core contributor, Creator of Nyan Keys, and Founder of QR Snap LLC, a QR Code redirection service with an emphasis on analytics. 

### Nyan Keys - FPGA USB2.0 HS Mechancial Keybaord
<div align="left">
 <img src="https://github.com/russeree/nyan-keys-stm32-firmware/raw/master/assets/images/icon_square.png" width="120" height="120">
</div>

An FPGA based mechanical keyboard designed for the lowest possible latency and programmability. The FPGA parallel subinterface allowing each key to be indexed in parallel. In addition to a high degree of flexibility using an FPGA has allowed for sub milisecond latency with low debounce time switches. Lower performance switches such as Cherry MX Blues (5ms debounce) can be used and still acheive the lowest possible latency for that switch.

This is the first true USB2.0 High Speed __NOT FULL SPEED__ keyboard to exist as such native 8000HZ polling rates occour without the need for drivers. The USB 2.0 High Speed spec also allows for up to 1024 bytes with each poll. As such the full NKRO set can be sent 8000 times a second. The report is not broken up into sections with each section being sent per interrupt. 

Nyan Keys has 4 Primary Components
 - [FGPA Bitstream](https://github.com/russeree/nyan-keys-ice40hx4k-bitstream)
 - [STM32 Firmware](https://github.com/russeree/nyan-keys-stm32-firmware)
 - [Web Serial API GUI - hosted](https://russeree.github.io/)
 - [Web Serial API GUI - Source](https://github.com/russeree/nyan-keys-gui)
 - [PCB Schematic and Layout](https://github.com/russeree/nyan-keys-hardware)

The performance of Nyan Keys when configured with Cherry MX2A ([sub 1ms bounce time](https://www.cherry-world.com/company/press/article/cherry-mx2a-exceeding-expectations)) can exceed that of the Wooting with true sub 1ms latency. 
 - [Original Reddit Post](https://www.reddit.com/r/FPGA/comments/17rt1rc/a_little_side_project_of_mine_fpga_based)

### Social Media and Contact Links
* [email](mailto:admin@qrsnap.io)
* [qrsnap.io](https://qrsnap.io)
* [twitter](https://twitter.com/PortlandHodl)
