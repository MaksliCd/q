cdhmea@Ubuntu:/var/www$ sudo ip a
[sudo] password for cdhmea: 
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host noprefixroute 
       valid_lft forever preferred_lft forever
2: enp0s3: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 08:00:27:21:3b:c6 brd ff:ff:ff:ff:ff:ff
    inet 10.0.2.15/24 brd 10.0.2.255 scope global dynamic noprefixroute enp0s3
       valid_lft 79969sec preferred_lft 79969sec
    inet6 fd00::ccfa:37dc:dde1:f20a/64 scope global temporary dynamic 
       valid_lft 86385sec preferred_lft 14385sec
    inet6 fd00::a00:27ff:fe21:3bc6/64 scope global dynamic mngtmpaddr 
       valid_lft 86385sec preferred_lft 14385sec
    inet6 fe80::a00:27ff:fe21:3bc6/64 scope link 
       valid_lft forever preferred_lft forever
