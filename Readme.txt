﻿SerialPortSample
Command-line tool demonstrating how to do serial I/O on Mac OS X.

Version: 1.3 - 10/15/2002

Techniques shown are:
- Finding a serial port
- Opening and configuring the port
- Sending an "AT" command to a modem attached to the port
- Reading the "OK" response from the modem (if any)
- Closing the port

Includes Project Builder 2.1, CodeWarrior 8.2 Mach-O, and Xcode 2.1 projects.

Version: 1.4 - 07/20/2005

- Updated to produce a universal binary.
- Added examples of setting arbitrary baud rates and the read timer latency. 
- Use kIOMasterPortDefault instead of older IOMasterPort function.
