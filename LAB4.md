# Admin II
Lab 4

1. Use fdisk -l to locate information about the partition sizes.

![Lab4-1](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab4-1.png)

2. Use fdisk to add a new logical partition that is 1GB in size.

![Lab4-2](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab4-2.png)

3. Did the kernel feel the changes? Display the content of /proc/partitions file? What did you notice? How to overcome that?

![Lab4-3](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab4-3.png)

4. Make a new ext2 file system on the new logical partition you just created.
Bonus: Try creating the ext2 filesystem with 2k blocks and one inode per every 4k (two blocks) of filesystem.

![Lab4-4](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab4-4.png)

5. Create a directory, name it /data.

![Lab4-5](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab4-5.png)

6. Add a label to the new filesystem, name it data.

![Lab4-6](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab4-6.png)

7. Add a new entry to /etc/fstab for the new filesystem using the label you just create.

![Lab4-7](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab4-7.png)

8. Mount the new filesystem.

![Lab4-8](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab4-8.png)

9. Display your swap size.

![Lab4-9](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab4-9.png)

10. Create a swap file of size 512MB.

![Lab4-10](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab4-10.png)

11. Add the swap file to the virtual memory of the system.

![Lab4-11](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab4-11.png)

12. Display the swap size

![Lab4-12](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab4-12.png)

13. Implement disk quotas for users on the /home directory by taking the following actions
        a. Edit /etc/fstab and add the usrquota option to the /home filesystem
        b. Remount the filesystem with the command mount -o remount /home
        c. Use the quotacheck command to create the quota-tracking file quotacheck /home
        d. Use the quotaon command to enable quota tracking by the kernel quotaon /home



