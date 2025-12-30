# Wiring Options

## Radio PoE or LumaSwitch (Recommended)
The simplest and most reliable method of wiring P1 is by utilizing the Vivid Hosting radio or [LumaSwitch](https://luma.vision/products/lumaswitch)'s PoE output.

![Radio PoE Diagram](img/Radio%20PoE%20Diagram.png){width="600"}


### Radio
Simply connect the radio to P1 with an ethernet cable and switch on the [PoE dipswitch](https://frc-radio.vivid-hosting.net/overview/wiring-your-radio#power-over-ethernet-poe-for-downstream-devices) for the port its plugged into.

### LumaSwitch
Connect an ethernet cable between P1 and one of the PoE ports on LumaSwitch. Use a 5A fuse to enable PoE on the chosen slot.

!!! warning
    When powering P1 via PoE, ensure you are using an ethernet cable that uses at least 24 AWG wire for each conductor. DO NOT use "low profile" ethernet cable.

## PoE Injector
If you do not wish to use PoE from the radio or would like to connect P1 to an ethernet switch, you can still power P1 via PoE by using a PoE injector or custom PoE cable. Use a 5A or 10A fuse in the slot powering the PoE injector or cable.

![Radio PoE Diagram](img/PoE%20Diagram.png){width="600"}

!!! warning
    When powering P1 via PoE, ensure you are using an ethernet cable that uses at least 24 AWG wire for each conductor. DO NOT use "low profile" ethernet cable.

## Weidmuller Connector
If not using PoE, or you would like to have redundant power, P1 can also be powered through the Weidmuller connector next to the ethernet port. Use a 5A or 10A fuse in the slot powering the device.

![Radio PoE Diagram](img/Weidmuller%20Diagram.png){width="600"}