installation of Gluster FS

 sudo fdisk /dev/vdb
 n

 p
 {enter}
 {enter}
 w

 
 sudo mkfs.xfs -i size=512 /dev/vdb1  
