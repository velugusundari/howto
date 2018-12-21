# Hello
## How Are You?
# End-to-end building solutions

##### Show casting the best in building technology and architectural creativity,The times of India ABI Expo 2018 aims to redefine building concepts, right from the foundation to interior design
            
###### The Indiam building and construction industry has played a vital roll in the overall development of the country over the years.While automation and innovation have been the focus of construction companies for a while now,with rising price affecting home spaces, the demond for comfortable, utility homes have seen a considerable boost of late.Thid has resulted in interior design becoming an integral part of the construction industry.

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

    
        
        
    
