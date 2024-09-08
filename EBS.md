 118  lsblk
  119  mkfs.ext4 /dev/xvdb
  120  mkdir /data-volume
  121  mount /dev/xvdb /data-volume
  122  df -h
  123  vim /etc/fstab
  124  blkid
  125  vim /etc/fstab
  126  vim /etc/fstab    ->UUID=a82d354e-552e-46ae-9168-a8d3d749821d /data-volume ext4 defaults 0 2
 yum install httpd
  136  cd /var/www/httpd
  137  cd /var/www/html
  138  ll
  139  vim index.html
  140  systemctl start httpd
  141  systemctl enable httpd


INCREASING EBS Volume ->Modify -> lsblk -> reize2fs <ebs destination>

DECREASING VOLUME
 Create new volume < existing volume → attach it to the machine/instance
 
