This is a repository to help you easily run opensimulator for OSGrid persistently

It uses the docker image for OSGrid opensimulator found at https://hub.docker.com/r/murf66/docker-osgrid/

All you need to do is clone this repo and run the following command:

docker-compuse up -d

For once-off first-time config, run the following command:

     $ docker exec -it os-osgrid-1 after_install.sh

Then respond the questions relate to virtual word : 

 - New region name []:     ==> need to entry region name that you want for it .(need to remember it).

 - RegionUUID [29923331-dddd-4acc-a3d8-46d3c129b6e3]:     ==> press enter key to keep the same.

 - Region Location [1000,1000]:                           ==> get a location from http://www.osgrid.org/index.php/opencoordinates

 - Internal IP address [0.0.0.0]:                         ==> press enter key to keep the same.

 - Internal port [9000]:                                  ==> press enter key to keep the same.

 - Allow alternate ports [False]:                         ==> press enter key to keep the same.

 - External host name [SYSTEMIP]:   ==> need to entry the external ip or your http address don't include the port.

 - New estate name [My Estate]:     ==> press enter or change it. 

 - Estate owner first name [Test]:  ==> use your osgrid firstname

 - Estate owner last name [User]:   ==> use your osgrid lastname

 - Password:                       ==> use your osgrid password

 - Email:                          ==> ..... 

 - User ID [6edd775a-8c1e-4a43-ad16-36df2af3ea0c]:  ==> press enter key to keep the same.

After some process it will show:

Region (.....) # 

 - 'quit' command to continue.


For more help on docker and docker-compose see:
https://www.docker.com/
