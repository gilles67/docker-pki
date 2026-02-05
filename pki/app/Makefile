all:
	apt-get update -y
	apt-get upgrade -y
	apt-get install -y --no-install-recommends lighttpd
	apt-get -y autoremove
	apt-get clean
	chmod a+x /app/lighttpd-run
	
	