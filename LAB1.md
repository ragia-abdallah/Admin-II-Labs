# Admin II
Lab 1

    1. Use systemctl to view the status of all the system services.

	>> systemctl list-unit-files --type service
![AdminII-Lab1-1](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/AdminII-Lab1-1.png)

    2. Change the default run level back to multi-user.target and reboot.

	>> systemctl set-default multi-user.target #setting default
	>> init 6 #rebooting
	>> sudo init 5 #loading GUI
![AdminII-Lab1-2](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/AdminII-Lab1-2.png)

    3. Send mail to the root user.

	>> mailx -s "Subjetct" root@local host
	Text
	EOT #Ctrl+d
![AdminII-Lab1-3](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/AdminII-Lab1-3.png)

    4. Verify that you have received this mail.

	>> su - root
	>> mailx
	& N
![AdminII-Lab1-4](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/AdminII-Lab1-4.png)

    5. Use  systemctl utility to stop postfix service

	>> systemctl stop postfix
![AdminII-Lab1-5](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/AdminII-Lab1-5.png)

    6. Send mail again to the root user.

	>> mailx -s "Subjetct" root@local host
	Text
	EOT #Ctrl+d
![AdminII-Lab1-6](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/AdminII-Lab1-6.png)

    7. Verify that you have received this mail.

	>> su - root
	>> mailx
	No New Mail Found
![AdminII-Lab1-7](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/AdminII-Lab1-7.png)

    8. Use systemctl utility to start postfix service

	>> systemctl start postfix
![AdminII-Lab1-8](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/AdminII-Lab1-8.png)

    9. Verify that you have received this mail.

	Notification of new mail
	>> mailx
	& N
![AdminII-Lab1-9](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/AdminII-Lab1-9.png)

    10. Edit in the GRUB2 configuration file and change the timeout variable equal 20 seconds.

	>> sudo vi /etc/default/grub
![AdminII-Lab1-10.1](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/AdminII-Lab1-10.1.png)
![AdminII-Lab1-10.2](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/AdminII-Lab1-10.2.png)

    11.  Edit in the GRUB2 configuration file and change your default operating system

![AdminII-Lab1-11](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/AdminII-Lab1-11.png)

    12. Install a new printer called "tty12" using web utility. Have the printer queue be "/dev/
tty12" and specify a "Text Only Printer" for its model type.

![AdminII-Lab1-12](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/AdminII-Lab1-12.png)


    13. Print the file /etc/hosts to the printer and view the /dev/tty12 console to ensure that the print job went to the "printer".

![AdminII-Lab1-13](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/AdminII-Lab1-13.png)

    14. Prevent jobs from leaving the tty12 printer queue to the printer. Do not prevent users from sending jobs to the tty12 printer queue.



    15. Print three files (/etc/hosts, /etc/xinetd.conf, and /etc/hosts.allow) to the tty12 printer



    16. View the print queue.



    17. Remove the second print job from the tty12 printer queue, and then allow the print jobs 
from the queue to be printed



    18. Prevent print jobs from going to the tty12 printer's print queue.



    19. Verify this by trying to print the /etc/hosts file.



    20. Delete the tty12 printer with the lpadmin command.



