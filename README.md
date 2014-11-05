NOP Security UKI1 mirror
========================

UKI1?
-----
I **love** NOP Security's USB Key Injector, a thumbdrive-sized attiny-powered virtual usb keyboard.

Instead of me rambling on about it, here's how NOP Security themselves described the project:

> The UKI (USB Key Injector) is an open-source (GPL) device that uses the USB HID interface (which is built into many operating systems) to inject keystrokes into a computer or device while it's running, without an actual keyboard. It uses an attiny85 processor and an optional 64k byte serial EEPROM. The scripts can be re-uploaded without having to reflash any firmware.

Awesome.

Unfortunately, about a week ago, the [UKI1 website](http://www.nopsecurity.net/UKI1.htm) dissapeared.
*Fortunately* I still had some of the downloads in my home folder, and most of the website in my browser cache.

Some parts are missing?
-----------------------

Yup, I didn't have all the downloads any more, and some of the images were only thumbnails, so they're lower quality than the originals. Most of the important stuff is there though:

 - the schematics
 - firmware and sourcecode
 - C++ source for the upload software

The upload software source is the Visual Studio version, but it should be easy to port the relevant code to other platforms.
