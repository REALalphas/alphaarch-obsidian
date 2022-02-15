##### I can't boot
1. Make grub again

##### I can't boot properly
1. If you have timeout when booted in Arch and error with UUID	
	###### Regenerate fstab
Mount partitions
Run `nano /mnt/etc/fstab`
Remove every line with UUID and drive names
Generate fstab again `genfstab -U /mnt >> /mnt/etc/fstab`
