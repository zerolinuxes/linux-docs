```bash

# To enable the apt repository

        sudo apt update

# to upgrade the installed packages

        sudo apt upgrade -y

# to restart the device
sudo reboot

# To find the flavours of linux
lsb_release -a

# To scan the service listening port
    nc -vz localhost 123
    
# To check the port is listening
    ss -tulpn | grep 123
   
# To create a user
    adduser aro
    
# To change passwd for a user
    passwd aro
    
# To create a group
    groupadd -g 123 jino
    
# To add a user in a existing group
    usermod -a -G jino aro jas
    
# To remove a user from existing group
    gpasswd -d jino aro
    
# To give sudo privileage to a user
    usermod -G sudo aro
    
# To see the group details
    cat /etc/groups
    
# To see the user details 
    cat /etc/passwd
    
# To create a folder
    mkdir aro
    
# To create a empty file in a directory
    touch aro.txt
    
# To create a multiple directory in a simgle command
    mkdir -p A/{A1,A2} B/{B1,B2}
    
# To create a file under a directory
    touch A/A1/A11.ttxt B/B1/B11.txt
    
# To switch to a folder 
    cd aro
    
# To come out of a directory
    cd
    
# To delete a directory use command
    rm -rf
    
# To give sudo privileage to a user without adding a sudo 
    visudo
    
# To change a hostname 
    hostnamectl set-oldhostname newhostname-server
    
# To check whether the packages installed or not
    dpkg --get-selections | grep apache2
    
# To check a ip address
    ifconfig -a
    
# To create a file with diffrent commands
        touch jino.txt
        echo > jino1.txt
        echo "hi arowin" > arowin.txt
        echo "hi jino" | tee jino2.txt
        vim arowin.txt
        
# To read the file
        cat jino.txt
        
vim editor shortcuts
        yy - copy
        p - paste
        :wq! - save and quit
        :q! - only quit
        u - undo
        dd - delete the entire line
        r - replace the cursor word
        
    
        # To find the flavors of linux in redhat
        cat /etc/redhat-release.
   
  
    
   # to find a running process in ubuntu
                ps -ef
                
                
 # to kill a process, use command
                kill -9 -processid


```
