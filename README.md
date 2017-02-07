# OpenKM

To run:

	docker run -dti --name openkm -v /srv/openkm/repository:/usr/local/tomcat/repository -p 8080:8080 ypaber/openkm
	
and access:

	http://docker_machine_ip:8080/ 
	
Default credential user: okmAdmin password: admin