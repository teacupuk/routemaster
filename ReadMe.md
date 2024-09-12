# Routemaster
Application designed to iterate through Windows machines on a specific IP range to pull out the static routes that have been assigned. 

## Framework
Standard building blocks of the program is: 
- User provides an IP address // range
- Program connects to the windows machine and uses route print to get the routes 
- Program stores and reports back on the status of the machine(s), default gateway, static routes etc
