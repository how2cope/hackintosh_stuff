# Skylake Sierra build guide without the need of an existing Mac computer or Hackintosh

![about](https://raw.githubusercontent.com/how2cope/hackintosh_stuff/master/images/about.png "about")


### My hardware:
* Mobo: ASUS Z170 Pro Gaming
* CPU: Intel i7-6700K Skylake
* GPU: MSI Nvidia GTX 970 4GB
* Memory: Kingston HyperX 2x8GB 2667 MHz DDR4
* System drive: Samsung 840 EVO 120 GB SSD
* Extra drives: 1x 3TB WD Red, 1x 4TB WD Blue and 1x 1TB Seagate SSHD (All NTFS, I use them on macOS using [Tuxera NTFS](https://www.tuxera.com/products/tuxera-ntfs-for-mac/))

### The guide I used:
[Ramblings of a Hackintosher - A (Sorta) Brief Vanilla Install Guide](https://www.reddit.com/r/hackintosh/comments/68p1e2/ramblings_of_a_hackintosher_a_sorta_brief_vanilla/)
The guide is written for High Sierra, but is perfectly usable for Sierra as well.

### Prerequisites:
* USB flash drive with 8+ gigs of storage (16 gigs recommended)
* Access to a legitimate copy of macOS Sierra, can be obtained in the [App Store](https://itunes.apple.com/us/app/macos-sierra/id1127487414?mt=12)
* Kexts (Kernel EXTensions), some are general and some are  related to your hardware, I'll get into that ramblings_of_a_hackintosher_a_sorta_brief_vanilla

### Preparing the virtual machine environment:
* The virtual machine is in Russian by default, you can change this in the System Preferences.





### Creating the bootable USB
I used a High Sierra virtual machine from RuTracker loaded into VMware Workstation on Linux to create my bootable USB.
