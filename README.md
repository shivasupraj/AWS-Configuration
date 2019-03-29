# Lightsail configuration for the ubuntu instance.

| Accessing server|                |
| --------------- |:-------------:|
| ssh host adress | 18.207.120.2  |
| port            | 2200          | 
|URL              |[18.207.120.2.xip.io](http://18.207.120.2.xip.io)|

Clone the repository Cloting-Catalog from [here](https://github.com/shivasupraj/Clothing-Catalog) to you machine and run `sudo apt update` to know all the packages which require updates and `sudo apt upgrade` to upgrade them. Then change the SSH port from default 22 to another number and configure the firewall to allow it. Configure the UFW to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123). 

## Packages installed
  * mod_wsgi
  * PostgreSQL
  * Psycopg2
  * Redis
  * Flask
  * Flask-httpauth
  * Sqlalchemy
  
## Useful resources
  * StackOverflow posts
  * GitHub repos
  * Udacity forum
