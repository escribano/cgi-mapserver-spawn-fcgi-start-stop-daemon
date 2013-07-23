cgi-mapserver-spawn-fcgi-start-stop-daemon
==========================================

combining cgi-mapserver spawn-fcgi and start-stop-daemon for nginx usage

Requirements (Ubuntu 12.04)

sudo apt-get install python-software-properties
sudo add-apt-repository ppa:ubuntugis/ubuntugis-unstable
sudo apt-get update

sudo apt-get install libgd2-xpm-dev
sudo apt-get install cgi-mapserver mapserver-bin
sudo apt-get install nginx
sudo apt-get install spawn-fcgi


Usage:

sudo /etc/init.d/mapserv-fcgi-daemon {start|stop|restart}
