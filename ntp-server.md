# NTP SERVER

Purpose of ntp service

    The Network Time Protocol (NTP) is a networking protocol for clock synchronization
    between computer systems over packet-switched, variable-latency data networks.


ntp server installtion package

    apt install ntp
    
ntp client installation package

    apt install ntpdate

ntp port number

    port number is 123

start the ntp service

    systemctl start ntpd
    
status the ntp service

    systemctl status ntpd
    
enable the ntp service

    systemctl enable ntpd
    
disable the ntp service

    systemctl disable ntpd
    
cat the ntp service

    systemctl cat ntpd
    
check the active ntp service

    systemctl is-active ntpd
    
check the enable status ntpd service

    systemctl is-enabled ntpd
    
 ntp configuration file location
 
    udo nano /etc/ntp. conf.
