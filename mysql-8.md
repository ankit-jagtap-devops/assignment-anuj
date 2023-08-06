# MySQL 8.0 packages are available on official MySQL Dev apt repository.

sudo apt update && sudo apt -y  install wget
wget https://repo.mysql.com//mysql-apt-config_0.8.22-1_all.deb
sudo dpkg -i mysql-apt-config_0.8.22-1_all.deb

# use below images for reference
https://computingforgeeks.com/wp-content/uploads/2018/11/install-mysql-8.0-debian-9-debian-8-01.png

https://computingforgeeks.com/wp-content/uploads/2018/11/install-mysql-8.0-debian-9-debian-8-02.png

https://computingforgeeks.com/wp-content/uploads/2018/11/install-mysql-8.0-debian-9-debian-8-02.png

# Once the repository has been added, install MySQL 8.0 on Debian 11/10/9 by running the following commands:

 wget https://dev.mysql.com/get/Downloads/MySQL-8.0/mysql-server_8.0.34-1debian11_amd64.deb-bundle.tar

 