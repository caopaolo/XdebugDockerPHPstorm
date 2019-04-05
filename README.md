# XdebugDockerPHPstorm
setting xdebug in PHPstorm with docker enviroment

#change xdebug.remote_host in xdebug.ini file
We can use my Macintosh's IP address. We use my Mac's private network IP address for the remote_host, as this configuration is telling xdebug where to reach PHPStorm, which will be listening on my host machine for xdebug connections.

# build the image and run it

docker-compose build
docker-compose up -d

#setting PHP storm



