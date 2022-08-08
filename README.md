# common-ubuntu-commands

Cancel local commit

	git reset HEAD~1
	
Convert odt to pdf  

	libreoffice --headless --convert-to pdf *.odt

Duplicate / copy  

    cp file_to_copy new_file

Copy files / folder to remote 

	rsync -rv /home/rodo/Documents/GitHub/supertrend-crypto-bot rodo@192.168.1.21:/home/rodo/Documents/GitHub

Rename / move  

	mv old_name new_name

Install Github Desktop:

    https://gist.github.com/berkorbay/6feda478a00b0432d13f1fc0a50467f1

Give access to bash script and run it

    chmod u+x bash-script.sh
    ./bash-script.sh

Turn on/off conservation mode (0: off, 1: on)

    echo 0 | sudo tee /sys/bus/platform/drivers/ideapad_acpi/VPC2004:00/conservation_mode

Edit file with text editor from terminal 

    gedit filename.txt
    
Count the number of items in a directory

    ls | wc -l

Remote control Pi Ubuntu

	1. Download and Install VNC Server from its website
	1. `systemctl start vncserver-virtuald.service`
	1. Enable 

Things to fix after having installed Ubuntu

	1. Disable secure boot
	(step 2 and 3 may not necessary if step 1 stops the problems: unable to control brightness, unable to resume after suspending)
	2. If brightness fn key is not functioning properly, do this https://forums.developer.nvidia.com/t/brightness-not-working-ubuntu-20-04-lenovo-legion-5-15imh05/178058/20 
	3. Switch to NVIDIA 470 driver in Software & Updates 
	4. Edit favorites 
	5. Install other softwares: VSCode, Zoom, OBS, VLC, etc.
	6. Move data in
	


