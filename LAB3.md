# Admin II
Lab 3

1. Display your MAC address by 2 different ways.

![Lab3-1.1](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-1.1.png)
![Lab3-1.2](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-1.2.png)

2. Display the network settings of all active interfaces.

![Lab3-2](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-2.png)

3. Display the network setting of all interfaces both active inactive.

![Lab3-3](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-3.png)

4. Bring your interface down.

![Lab3-4](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-4.png)

5. Configure your network card to have static IP.

![Lab3-5.1](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-5.1.png)
![Lab3-5.2](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-5.2.png)
![Lab3-5.3](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-5.3.png)
![Lab3-5.4](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-5.4.png)

6. Bring your interface up.

![Lab3-6](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-6.png)

7. Verify your network setting using ifconfig command

![Lab3-7](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-7.png)

8. Configure your network card to have dynamic IP using network manager command.

![Lab3-8](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-8.png)

9. Check using ifconfig then check its configuration file.

![Lab3-9](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-9.png)

10. Reconfigure your network card using system-config-network utility to have static IP.

![Lab3-10](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-10.png)

11. Configure your network card to have 3 IPs and check that they are all working using ifconfig command.

![Lab3-11](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-11.png)

12. Change your host name in your global network file.

![Lab3-12](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-12.png)

13. Check the present value of /proc/sys/net/ipv4/icmp_echo_ignore_all

![Lab3-13](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-13.png)

14. It should be 0, change it to 1 which will prevent other hosts from successfully pinging your host while not affecting your ability to ping them.

![Lab3-14](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-14.png)

15. Try to ping your colleague, let your colleague try to ping your host.

![Lab3-15](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-15.png)

16. Reboot and try the last step. What happened? Why?

![Lab3-16](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-16.png)

17. Edit /etc/sysctl.conf and put the following line at the bottom:
net.ipv4.icmp_echo_ignore_all=1

![Lab3-17](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-17.png)

18. Execute sysctl –p command.

![Lab3-18](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-18.png)

19. Check the value of /proc/sys/net/ipv4/icmp_echo_ignore_all.

![Lab3-19](https://github.com/ragia-abdallah/Admin-II-Labs/blob/main/AdminII/Lab3-19.png)



