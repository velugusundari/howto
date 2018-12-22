# Hello
## How Are You?
# End-to-end building solutions

## centOS 7 Notes

### Terminal prompt meanings
        $ means normal user
        # means root

### Check OS version 
        rmp --query centos-release
            
### Update
        Checks for updates and asks for confirmation
        yum -y update
        
### Install tmux
        # yum install epel-release
        # yum install tmux
        
### Install wget
        # yum install wget
        
### Install golang 1.8
        Download
        # wget http://storage.googleapis.com/golang/go1.8.linux-amd64.tar.gz
        
        Install to /usr/local
        # tar -c /usr/local -xzf go1.8.linux64.tar.gz
        
        Append golang location to path variable and add it to /etc/profile file
        # echo "export PATH=$PATH:/user/local/go/bin" >> /etc/profile
        
        Default GOPATH=$HOME/go
        go get and go install - location add to path variable
        
        # echo "expo PATH=$PATH:HOME/go/bin" >> /etc/profile
        
        Check golang version
        # go version
        
### Install gotty
        # go get github.com/yudai/gotty
        
### Install postgresql
        List packages beings with postgresql
        # yum list postgresql*

    
        
        
    
