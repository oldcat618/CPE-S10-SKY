# CPE-S10-SKY
创维Swaiot 5G CPE

分区信息

M01MX# smem
flash_type:             0x6
flash_index:            0x0
flash_chip_select:      0x0
flash_block_size:       0x10000
flash_density:          0x1000000
partition table offset  0x0
No.: Name             Attributes            Start             Size
  0: 0:SBL1           0x0000ffff              0x0          0x50000
  1: 0:MIBIB          0x001040ff          0x50000          0x10000
  2: 0:BOOTCONFIG     0x001040ff          0x60000          0x20000
  3: 0:BOOTCONFIG1    0x001040ff          0x80000          0x20000
  4: 0:QSEE           0x0000ffff          0xa0000         0x180000
  5: 0:QSEE_1         0x0000ffff         0x220000         0x180000
  6: 0:DEVCFG         0x0000ffff         0x3a0000          0x10000
  7: 0:DEVCFG_1       0x0000ffff         0x3b0000          0x10000
  8: 0:APDP           0x0000ffff         0x3c0000          0x10000
  9: 0:APDP_1         0x0000ffff         0x3d0000          0x10000
 10: 0:RPM            0x0000ffff         0x3e0000          0x40000
 11: 0:RPM_1          0x0000ffff         0x420000          0x40000
 12: 0:CDT            0x0000ffff         0x460000          0x10000
 13: 0:CDT_1          0x0000ffff         0x470000          0x10000
 14: 0:APPSBLENV      0x0000ffff         0x480000          0x10000
 15: 0:APPSBL         0x0000ffff         0x490000          0xa0000
 16: 0:APPSBL_1       0x0000ffff         0x530000          0xa0000
 17: 0:ART            0x0000ffff         0x5d0000          0x40000
 18: 0:ETHPHYFW       0x0000ffff         0x610000          0x80000
 19: ledeinfo         0x0000ffff         0x690000          0x10000
 20: reserve          0x0000ffff         0x6a0000          0x10000
 21: rootfs           0x0100ffff        0x3c00000        0x3400000
 22: 0:WIFIFW         0x0100ffff        0x7000000         0x800000
 23: rootfs_1         0x0100ffff              0x0        0x3400000
 24: 0:WIFIFW_1       0x0100ffff        0x3400000         0x800000
