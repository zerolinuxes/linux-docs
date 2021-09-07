##### DNS (DOMAIN NAME SERVER)

purpose of domain name server

    DNS is used to associate the domain name with appropriate ip address
    
port number for dns

    port number is 53
    
to install dns server package 

    apt install bind9
    
to install the dns client package

    apt install dnsutils
    
host command usage
host command is used to get ip address and all information

   
   host -a domainname
    
nslookup usage
nslookup is used to get information about domain name server
    
    nslookup domainname
    
to start a dns service 

        systemctl start bind9
        
to stop a dns service

        systemctl stop bind9
        
to check the service running or not

        systemctl status bind9

        
    
 
