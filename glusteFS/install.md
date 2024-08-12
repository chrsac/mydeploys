installation of Gluster FS

 sudo fdisk /dev/vdb
 
 n
 
 p
 
 {enter}
 
 {enter}

 {enter}
 
 w

 
 sudo mkfs.xfs -i size=512 /dev/vdb1  

Add an entry to /etc/fstab

echo "/dev/vdb1 /export/vdb1 xfs defaults 0 0"  >> /etc/fstab

mkdir -p /export/vdb1 && mount -a



