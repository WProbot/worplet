# Worplet - a WordPress droplet
### Get WordPress spinning on a VPS at warp speed

### Prerequisites

- VPS server with root access running Ubuntu 18.04 LTS
- Registered domain with DNS pointing to VPS server
- Works with 'localhost' also
- Works with sever external IP also

### Description

- Shell script that allows for an easy setup of a Linux server with php, mysql, nginx, wordpress, domain and ssl. All you need to quick start your development and skip the server setup manual labor.

### Results

- VPS server will be running on latest WordPress installation
- VPS server will install PHP, MySQL and Nginx
- VPS server will create and populate new mysql database
- VPS server will create and configure all services without interaction
- VPS server will setup the domain and install an SSL certificate
- WordPress site files will be available in `/root/var/www/html/wordpress`


## How to use

### install git

`sudo apt install git -y`

### clone repository

`git clone https://github.com/fountainpositive/worplet.git worplet`

### run

`cd worplet && sudo chmod +x *` 

`sudo ./run.sh`

## Startup script for VM (IP only)

### install git

`sudo apt install git -y`

### get startup file

`sudo wget https://raw.githubusercontent.com/fountainpositive/worplet/master/startup.sh`

### run

`sudo chmod +x startup.sh` 

`sudo ./startup.sh`

Copyright (c) 2019-2020, fountainpositive

Published under GNU GENERAL PUBLIC LICENSE.
More info: https://www.gnu.org/licenses/
