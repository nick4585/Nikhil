  
Partitions:-
      Partitions are divisions in the formatting of the hard disk.It allow us to divide are hard drive into isolated section where each section behaves as its own hard
drive.It is useful if we run multiple operating system.There are lots of powerful tools for creating, removing and otherwise manipulating disk partitionsin Linux.
Steps to create a partition:
             1. list partitions.
             2. label a partition.
             3. Use mkpart to make a partition.
             4. let the partition be created/settle.
             5. Attach the file system to the partition.
             6. Create a Mount point directory.
             7. Add entry in fstab.
             8. Systemctl daemon-reload.
             9. Mount the partition on the directory.
            10. Reboot.
 
           
 Commands:
             1.list block with UUID Lsblk - fs /dev/vdb
             2.list partitions - parted -l
             3.make label to a partition - parted /dev/vdb mklabel msdos
             4.create a partition - mkpart
             5.wait till partition is registered successfully - udevadm settle
             6.format file system with XFS file system - mkfs.xfs /dev/vdb1
             7.restart daemon service- systemctl daemon-reload.