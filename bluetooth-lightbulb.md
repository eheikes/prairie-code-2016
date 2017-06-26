# Reverse Engineering a Bluetooth Lightbulb

jessephelps.com

Goal: LED light to pulse when running build, green/red when finished

## Bluetooth Low Energy (BLE)

* Generic Attributes (GATT) to read/write
* key/value pairs

## TeamCity

* build system
* running in Docker container
* tcWebHooks

## Intel Edison

* compute board
* BLE chip (Blue Smurf) didn't support GATT

## Lightbulb

* Flux multicolor LED ([bluetoothlightbulb.com](http://bluetoothlightbulb.com/))

## Packet Capture

* BT Snoop on phone

## Together

* Node running on Edison
* TeamCity notifies web hooks
* Noble npm pkg

## Process

* `gatttool -I` CLI
* `rfkill unblock bluetooth` to kill BT
* `bluetoothctl` CLI
