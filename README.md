# Copy Partitions flashable zip

This is a flashable zip that helps you automatically copy slot A/B.

# Why the device needs to copy partitions

The third-party ROM will automatically switch to the inactive partition and flash it.

But on Motorola devices, the content of the inactive partition may not be up-to-date, downgrading the bootloader partition may cause the device enter to EDL mode, you will not be able to save it without blankflash, downgrading the baseband can also cause the device to be unrecognized.

It is used to keep the version of some important A/B partitions consistent, such as baseband, bootloader etc.
