# NovaOS Build Notes

NovaOS targets amd64 PCs and uses an XFCE desktop.

The release build must:
1. Use a supported Ubuntu/Xubuntu 24.04 build environment.
2. Produce a bootable ISO with a valid live environment.
3. Be tested in a virtual machine before release.
4. Be tested from a USB in live mode before installation.
5. Never repartition or modify the developer's Windows disk
   during the cloud build.

The configuration file describes the intended design; it does
not itself create an ISO.
