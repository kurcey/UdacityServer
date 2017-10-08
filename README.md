# UdacityServer

IP Address of server 34.203.54.12
SSH port 2200
web application url http://34.203.54.12/

Software installed:  
  libapache2-mod-wsgi
  apache2
  postgresql
  sqlite

python installed librarys:
  pip
  requests
  oauth2client
  sqlalchemy
  flask
  
  Setting edited:
      /etc/ssh/sshd_config
          adjust port to 2200
          PermitRootLogin no
          
      /etc/apache2/sites-enabled/000-default.conf
          adjusted wsgi file target for webserver
          
      NTP
          adjust to UTC timezone
          
      UFW
          locked out all ports except
           web (80)
           ssh (2200)
           NTP (123)
           
   Third party resources used:
          libapache2-mod-wsgi
          apache2
          postgresql
          sqlite
          pip
          requests
          oauth2client
          sqlalchemy
          flask
          NTP
          UWF
          ssh-keygen
          
  
          
     
  
