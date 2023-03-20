su  
sudo fdisk -l  
sudo fdisk /dev/nvme0n1 (for me i need " Disk /dev/nvme0n1: 953.87 GiB " )  
p  

Command (m for help): p  
Disk /dev/nvme0n1: 953.87 GiB, 1024209543168 bytes, 2000409264 sectors  
Disk model: addlink M.2 PCIE G3x4 NVMe  
Units: sectors of 1 * 512 = 512 bytes  
Sector size (logical/physical): 512 bytes / 512 bytes  
I/O size (minimum/optimal): 512 bytes / 512 bytes  
Disklabel type: gpt  
Disk identifier: X  
  
Device              Start        End    Sectors   Size Type  
/dev/nvme0n1p1       2048     206847     204800   100M EFI System                   (1)  
/dev/nvme0n1p2     206848     239615      32768    16M Microsoft reserved           (2)  
/dev/nvme0n1p3     239616 1999124479 1998884864 953.1G Microsoft basic data         (3)  
/dev/nvme0n1p4 1999124480 2000406527    1282048   626M Windows recovery environment (4)  
  
Command (m for help): d  
Partition number (1-4, default 4): 1,2,3,4  

1  
d  
2  
d  
3  
d  
4  
d  

