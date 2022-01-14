deb-nginx-xymon
process to run xymon on nginx
apt install nginx xymon apache2-utils fcgiwrap
https://www.nginx.com/resources/wiki/start/topics/examples/fcgiwrap/
follow the guide
https://blog.feld.me/posts/2014/11/setting-up-xymon-with-nginx/
Replace the /usr/local/www with the XYMONSERVERROOT="use/this/path" located in xymonserver.cfg
then update the fastcgi_pass to /var/run/fcgiwrap.socket;
