---
description: OctoPrint on Ender 3 V3 SE
---

# Octoprint

Technically there is no "OctoPrint on Ender 3 V3 SE" as you won't be installing any firmware. All it takes is to install OctoPrint on a computer connected by USB-C cable to the printer and you're set for the most part.

OctoPrint will communicate with stock Marlin firmware providing remote controls, job monitoring, telegram notifications and much more with a good number of available plugins. I've heard it can be even installed on mobile phone connected to printer yet I have not tested this.

#### Installation and configuration

1. Get a PC/RPi/whatever capable of running debian type system and prep it until you're SSH'ed into.
2. Get [KIAUH](https://github.com/dw-0/kiauh) and install Octoprint.

Yeah, that's it. Rest of the configuration is done via webUI which defaults to your-controller-ip:5000.

Alternatively you can use dedicated OctoPi OS by following [these instructions](https://octoprint.org/download/).

For more information check out [OctoPrint Community](https://community.octoprint.org/) site.
