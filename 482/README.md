# PS3 NAND/NOR Flash Writer
<br/>
[3.56 and Lower Minimum Version Supported]

Official Thread:
http://www.psx-place.com/threads/ps3xploit-tools-v2-0-improved-flash-writers-dumpers-even-easier-to-install-cfw-on-4-82-ofw.16139/

v2.0

    Freeze issues - Fixed
    Occasional bad dumps - Fixed
    No beeps & shutdown. Replaced by a graceful ROP chain exit & return to browser. This gives the opportunity to the user to dump after patching & validate the dump with littlebalup's py checker. As long as the user does not shutdown/restart, it's still possible to recover from bad patching.
    Support for usb port 0,1,6 + sd/cf/ms cards.
    Multi firmware support on all dumpers (4.10+) & DEX support on 4.81.
    HDD editions for all dumpers & flash writer where a picture file placeholder is used for read/write operations.
    Javascript refactoring for performance & efficiency.
    ps3xploit.com will host the 2.0 update, no need for 3rd party sites.


v1.0 (Thanksgiving 2017 Release)

    Supports Direct OFW to CFW patching for All Phat and 2xxx Slim (minver 3.56 Dec 2010 and lower)
    the NOR/NAND writer will just copy 3Mb of CoreOS data to both ros0 & ros1 in the flash memory.
    There is only one version released for 4.82. The same hex patch file can be used on nor & nand.
    It's as safe as possible, with a check for usb device & patch file making the exploit hang instead of corrupting flash if file is not found.
    In case of corruption (extremely rare but could always happen), it's only a partial brick because no per console info ever gets erased so a hardware flasher could still be used if ever a recovery reboot was impossible

