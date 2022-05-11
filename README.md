# openstack
Scripts used in openstack 
Download, Convert and Create image for openstack
1.Downlaod image
2.Convert
  qemu-img convert -O raw -f qcow2  file.img file.raw
3.Create and use
  openstack image create --public --disk-format raw --container-format bare --file file.raw [Display name]

if you have any question contact me by: mr.gerami@gmail.com
