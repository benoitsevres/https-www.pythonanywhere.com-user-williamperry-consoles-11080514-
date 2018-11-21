# https-www.pythonanywhere.com-user-williamperry-consoles-11080514-
# /* C P / M   B A S I C   I / O    S Y S T E M    (B I O S)
#  uses the BIOS INT13 call to access the disk
# Also different Linux kernels may assign different geometries to the same disk. Also, enabling or disabling 
# the BIOS of a SCSI card may change the fake geometry of the connected SCSI disks.
# definition of alignment? MSDOS 6.22 FDISK will do the following: 1. If the first sector of the cylinder is a partition table sector,
# then the rest of the track is unused, and the partition starts with the the next track. 
# https://www.tldp.org/HOWTO/Large-Disk-HOWTO-6.html
# JUNE, 1975 */
# […]
# /*  B A S I C   D I S K    O P E R A T I N G   S Y S T E M  (B D O S)
