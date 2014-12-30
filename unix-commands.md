Basic UNIX commands
=========

My simple reminder about command line ;)

#Files

    - ls
	- ls -l 
	- la -a
	- more _filename_
	- emacs _filename_
	- mv filename1 filename2
	- cp filename1 filename2
	- rm filename
	- diff filename1 filename2
	- wc filename
	- chmod options filename

#Directories

	- mkdir dirname
	- cd dirname
	- pwd

#Finding things

	- ff
	- grep string filename(s)

#About other people

	- w
	- who
	- finger _username_
	- last -1 _username_
	- talk _username_
	- write _username_
	- elm

#About your (electronic) self
	- whoami
	- finger
	- passwd
	- ps -u _username_
	- kill PID
	- quota -v
	- du _filemane_
	- last _yourusername_

#Connecting to the outside world
	
	- nn
	- rlogin _hostname_
	- telnet _hostname_
	- ftp _hostname_
	- lynx

#Miscellaneous tools

	- webster _word_
	- date
	- cal


#Network

	- ifconfig –a
	- ifconfig eth0
	- ip addr show
	- ip address add 192.168.0.1 dev eth0
	- ethtool eth0
	- mii-tool eth0
	- ping _host_
	- whois _domain_
	- dig _domain_
	- dig -x _host_
	- host google.com
	- hostname –i
	- wget file
	- netstat -tupl

#Compression / Archives

	- tar cf home.tar home
	- tar xf file.tar
	- tar czf file.tar.gz files
	- gzip file

#Install Package
	
	- rpm -i pkgname.rpm
	- rpm -e pkgname
	  Install from source ./configure 
	  make 
	  make install

#Disk Usage
	
	- df -h
	- df -i 
	- fdisk -l
	- du -ah
	- du -sh
	- findmnt
	- mount device-path mount-point

#Statics

	- top
	- mpstat 1
	- vmstat 2
	- iostat 2
	- tail -n 500 /var/log/messages
	- tcpdump -i eth1
	- tcpdump -i eth0 'port 80'
	- lsof
	- lsof -u testuser
	- free –m
	- watch df –h

#Others
	
	-