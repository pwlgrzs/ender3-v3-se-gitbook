# More about remote control

#### Why this page even exists?

Well, maybe like me you don't have space in your apartment but have a garage, or a shed, or just your kid wants to eat your filament. Either way, I needed a way to monitor jobs and generally speaking control printer remotely. Or maybe you just want to root and hack any device that can be. Like me making vacuum cleaner speaking GLaDOS voice.

There are 2 possible ways of doing this:

* staying on stock firmware and remote controlling with Octoprint (easier)
* flashing klipper firmware and instlling "klipper suite" (more features, but requires more investments and work with tuning)

Note: Klipper firmware is totally reversible to stock.

Technically, you can even have both OctoPrint and Klipper web UI installed on your controller and just swap firmwares from Marlin to Klipper and the other way while keeping your web UI plugins/settings.

#### What do you need?

There are 2 parts to remote controlling the printer, one is firmware that you will install on the printer (if going klipper way), other is the "controller" to that firmware that must run on a device connected to printer. That device can be Raspberry Pi (or other board running debian or clones), that could be a thin client like Fujitsu S920, old mobile phone or even a VM on your own PC with USB connected to virtual port on said VM. Choice is yours.

Raspberry Pi Zero 2W is cheap and will do (may be lacking firepower if you decide to run a FHD camera to watch the prints). I noticed OctoPrint is more CPU hungry than klipper things, but I do not have any free RPis to check.

Additionally you need a USB-C cable to connect controller to the printer, maybe a USB hub if you want camera.

I am probably offending half of the internet using word klipper controller (or suite) but that's what makes most sense IMHO for newbies.

#### Cool, what now?

As mentioned above you have two options:

* [OctoPrint](octoprint.md)
* [Klipper](klipper.md)

Read more about them in their sections. I am not going to make your mind of any.
