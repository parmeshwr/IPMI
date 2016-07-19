# IPMI

better reset the network setting toggeling to dhcp ans static


    ipmitool lan set 1 ipsrc static
    
    
    ipmitool lan set 1 ipaddr 10.94.149.102
    
    
    ipmitool lan set 1 netmask 255.255.255.0
    
    
    ipmitool lan set 1 defgw ipaddr 10.94.149.255
    
    
    ipmitool lan set 1 arp respond on
    
    
    ipmitool lan print
