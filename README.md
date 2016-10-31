# Drone
To install Drone, first install Docker using "wget -qO- https://get.docker.com/ | sh" <br />
Make sure Docker is running and then install Drone dependancies with apt-get such as libsqlite3-dev <br />
Download Drone with "wget downloads.drone.io/master/drone.deb" and depackage it with "dpkg -i drone.deb" <br />
Register Drone as a developer application on your GitHub and update the configuration file with the client ID and secret <br />
Uncomment the Wroker section in the Drone config file <br />
Restart the Drone service <br />
Update firewall to allow the secified port (8080 in this example, 80 by default) <br />
add a .drone.yaml file to start builds
