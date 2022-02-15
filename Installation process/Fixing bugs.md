##### I can't boot
1. Make grub again

##### I can't boot properly
1. If you have timeout when booted in Arch and error with UUID	
	**Regenerate fstab** ^de92a8
	1. In archiso mount partitions
	2. Run `nano /mnt/etc/fstab`
	3. Remove every line with UUID and drive names
	4. Generate fstab again `genfstab -U /mnt >> /mnt/etc/fstab` ^7ac026
