```bash

# To enable the apt repository
sudo apt update

# to upgrade the installed packages
sudo apt upgrade -y

# to restart the device
sudo reboot

# To find the flavours of linux
lsb_release -a

to scan the service listening port
    nc -vz localhost 123
    
to check the port is listening
    ss -tulpn | grep 123
   
to create a user
    adduser aro
    
to change passwd for a user
    passwd aro
    
to create a group
    groupadd -g 123 jino
    
to add a user in a existing group
    usermod -a -G jino aro jas
    
to remove a user from existing group
    gpasswd -d jino aro
    
to give sudo privileage to a user
    usermod -G sudo aro
    
to see the group details
    cat/etc/groups
    
to see the user details 
    cat/etc/passwd
    
to create a folder
    mkdir aro
    
to create a empty file in a directory
    touch aro.txt
    
to create a multiple directory in a simgle command
    mkdir -p A/{A1,A2} B/{B1,B2}
    
to create a file under a directory
    touch A/A1/A11.ttxt B/B1/B11.txt
    
to switch to a folder 
    cd aro
    
to come out of a directory
    cd
    
to delete a directory use command
    rm -rf
    
to give sudo privileage to a user without adding a sudo 
    visudo
    
to change a hostname 
    hostnamectl set-oldhostname newhostname-server
    
to check whether the packages installed or not
    dpkg --get-selections | grep apache2
    
 to check a ip address
    ifconfig -a
    

    



```
