# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

*add user feature
* install redis 
for ubuntu dev...
 install redis: sudo apt install redis-server
 configuration:
 open config file with your favorite editor
 sudo subl /etc/redis/redis.conf

 Inside the file, find the supervised directive
 and 
 add replace "no" by "systemd" after supervised


 Note important: The supervised directive is set to no by default. Since you are running Ubuntu, which uses the systemd init system, change this to systemd:

restart redis server:

 sudo systemctl restart redis.service
# LnTask
Redis config link : https://www.digitalocean.com/community/tutorials/how-to-install-and-secure-redis-on-ubuntu-18-04
