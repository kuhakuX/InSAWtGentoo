su  
fdisk -l  
[root@candy candy]# fdisk -l  
Disk /dev/sda: 111.79 GiB, 120034123776 bytes, 234441648 sectors  
Disk model: GALAX GXTA1C0120  
Units: sectors of 1 * 512 = 512 bytes  
Sector size (logical/physical): 512 bytes / 512 bytes  
I/O size (minimum/optimal): 512 bytes / 512 bytes  
Disklabel type: gpt  
Disk identifier: X  
  
Device        Start       End   Sectors  Size Type  
/dev/sda1      2048   1048575   1046528  511M EFI System  
/dev/sda2   1050624  41943039  40892416 19.5G Linux filesystem  
/dev/sda3  41943040 234440703 192497664 91.8G Linux filesystem  
  
  
Disk /dev/nvme0n1: 953.87 GiB, 1024209543168 bytes, 2000409264 sectors  
Disk model: addlink M.2 PCIE G3x4 NVMe  
Units: sectors of 1 * 512 = 512 bytes  
Sector size (logical/physical): 512 bytes / 512 bytes  
I/O size (minimum/optimal): 512 bytes / 512 bytes  
Disklabel type: gpt  
Disk identifier: X  
  
Device              Start        End    Sectors   Size Type  
/dev/nvme0n1p1       2048     206847     204800   100M EFI System  
/dev/nvme0n1p2     206848     239615      32768    16M Microsoft reserved  
/dev/nvme0n1p3     239616 1999124479 1998884864 953.1G Microsoft basic data  
/dev/nvme0n1p4 1999124480 2000406527    1282048   626M Windows recovery environment  
  
  
Disk /dev/mapper/luksdev: 19.48 GiB, 20920139776 bytes, 40859648 sectors  
Units: sectors of 1 * 512 = 512 bytes  
Sector size (logical/physical): 512 bytes / 512 bytes  
I/O size (minimum/optimal): 512 bytes / 512 bytes  
  
  
Disk /dev/zram0: 4 GiB, 4294967296 bytes, 1048576 sectors  
Units: sectors of 1 * 4096 = 4096 bytes  
Sector size (logical/physical): 4096 bytes / 4096 bytes  
I/O size (minimum/optimal): 4096 bytes / 4096 bytes  
  
  
Disk /dev/mapper/ainstsda3: 91.77 GiB, 98542026752 bytes, 192464896 sectors  
Units: sectors of 1 * 512 = 512 bytes  
Sector size (logical/physical): 512 bytes / 512 bytes  
I/O size (minimum/optimal): 512 bytes / 512 bytes  
  
me = /dev/nvme0n1p3     239616 1999124479 1998884864 953.1G Microsoft basic data ( 953.1G ) that what i need  
