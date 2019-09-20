# Z80-MBC2-ATMEL1284
This project contains a branched version of the Z80-MBC2 firmware.
It is my intention to use the additional facilities of the ATMEL1284 microcontroller to add features to the original.

Acknowledgement

Original software and hardware documentation can be found here (https://github.com/SuperFabius/Z80-MBC2.git) 
and I duly acknowledge the rights of the original author.  The original Arduino Bootloader - MightyCore - 
can be found here (https://github.com/MCUdude/MightyCore.git)

History

20-Sep-2019 - Mark Riley
	Branched "S220718-R280819_IOS-Z80-MBC2" to create "Z80-MBC2-ATMEL1284".
	Created this "README".
	Modified "Z80 BOOT" section of arduino file to use registers TCCR2B, TCCR2A, OCR2A and bits COM2A0, COM2A1.
	Reformatted existing files to improve legibility for me (This code now adheres to my standards, YMMV).
	Added "LICENSE" and original Author's "README" to this project.
