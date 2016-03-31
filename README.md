# Enttoi Adruino client

The client that built from two Adruino boards:
* First one installed in cabin itself and has sensors connected to it. This board
sends state of sensor via RF transmitter to the second board.
* Second one installed in place where LAN socket is available. RF receiver receives signals from the first board
and forwards it to the [gateway](https://github.com/Enttoi/enttoi-gateway) via LAN.

This solves an issue with unreliable WiFi connections or lack of such in cabins.

## Board schematic

The following parts required:
* Two Arduino boards
* RF Receiver/Transmitter module
* LAN connector
* 2 [reed switches](http://www.aliexpress.com/item//32424305003.html)
* LCD Screen (optional)
* Two 5V USB power adapters
* Wires

The parts needs to be connected in the following way:
