# BIOS and Other Settings for Ubuntu

## BIOS
Fastbook: Disabled
Launch CSM: Disabled
Secure Boot: Disabled

## OS Selection
*(Some BIOS machins require this)*
- On machines with other OS / Windows 10: Other OS
- On machines with Windows 7 / Windows 8.X: Windows 7

## Installing on New Disk Drives
1. Open GParted
2. Create a new partition table (MSDOS)
3. Create an EFI-ready partition
- FAT32
- About 200–400MB (200MB is more than enough unless you have a good reason otherwise)
- Boot flag
4. Now it is "EFI-ready"
5. When installing Ubuntu
- "Something else"
- Select this EFI-ready partition to use as EFI partition


## Great how-to video
(Windows 10 Ubuntu Dual Boot Tutorial | BIOS and UEFI partitions configuration on Asus X553MA)[https://www.youtube.com/watch?v=AbTpB6_677Q]
