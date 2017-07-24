# Udacity Full Stack Nanodegree - Linux Server Configuration
This project is to secure and setup a Linux Server on AWS Lightsail. 

## Public Address
```
IP Address: 52.56.94.216
SSH Port: 2200
```

## SSH connection details
```
=> ssh grader@52.56.94.216 -p 2200
=> Grader paswd: 123
```


## Required Packages
1. Install Apache 
2. Install Flask
3. Install PIP
4. Install SQLAlchemy
5. Install PostgreSQL
6. Install mod-wsgi

## Setting up the "UFW" Firewall
```  
  $ sudo ufw default deny incoming
  $ sudo ufw default allow outgoing
  $ sudo ufw allow 2200/tcp
  $ sudo ufw allow www
  $ sudo ufw allow ntp
  $ sudo ufw enable
```

### External resources:
Thanks to [Jai Kathuria](https://github.com/jaikathuria/FullStack-Project--8)
