# Red Hat Enterprise Linux (RHEL)

## Some Commands practising

1.		
	1) gzip:
		gzip txt_file		(txt_file.gz is just created)
		gunzip txt_file.gz

	3) zip:
		zip txt_file.zip txt_file
		unzip txt_file.zip

	
	Difference between compress and gzip commands:    
	Compression => Compress command replaces the original file with a new file that has a .Z extension.     
	gzip commands => The gzip command reduces the size of files.     
  The original file is replaced by a file with the same name & a .gz extension.        
	
2.	gzip -l txt_file.zip 	OR 	tar -tf test.gz

3.	sudo tar -cvf etc_backup.tar /etc	

4.	sudo find /home -mtime 2		

5.	sudo find /etc -user root	

6.	find /home -type d	

7.	locate .profile	

8.	file /etc/passwd /dev/pts/0 /etc /dev/sda
	
9.	ls -i / /etc /etc/hosts

10.	sudo cp /etc/passwd /home (file copied as passwd)
	diff /etc/passwd passwd
	cmp /etc/passwd passwd
	it's not permitted to write to it so, => sudo chmod 777 passwd
	vi passwd => make some changes => press 'esc' and :wq (write and quit) finally press enter to save
	now try again
	diff /etc/passwd passwd
	cmp /etc/passwd passwd	
		
11.	ln -s /etc/passwd /boot	

12.	ln /etc/passwd /boot (No I couldn't because file already exists)

This README.md file needs to be updated professionally.
