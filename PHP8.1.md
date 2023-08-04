# By default debian have not have any php 8.1 in its repo. To update repo for php 8.1

# to login as a root user

$ sudo -i 

$ sudo apt-get install ca-certificates apt-transport-https software-properties-common -y

# Once all the packages are installed, add a Sury repository to APT using the following command:

$ echo "deb https://packages.sury.org/php/ $(lsb_release -sc) main" | tee /etc/apt/sources.list.d/sury-php.list

# Next, download and add the GPG key with the following command:

$ wget -qO - https://packages.sury.org/php/apt.gpg >> /trusted.gpg.d

# Once you are done update the repository with the following command

$ apt-get update -y

# Now, you can install the PHP 8.1 using the following command:

$ sudo apt-get install php8.1 -y
