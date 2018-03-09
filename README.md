# IPMI

better reset the network setting toggeling to dhcp ans static


    ipmitool lan set 1 ipsrc static
    
    
    ipmitool lan set 1 ipaddr <New IP address>
    
    
    ipmitool lan set 1 netmask <Net mask>
    
    
    ipmitool lan set 1 defgw ipaddr <Gateway>
    
    
    ipmitool lan set 1 arp respond on
    
    
    ipmitool lan print
