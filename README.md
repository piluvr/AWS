#AWS DOCUMENTATION
1. Set up redhat aws instance with private keys using aws console
ssh -i /path/to/key.pem  ec2-user@instance.domain.here
2. ssh into it with keys and install apache, php, mariadb, mysql
dnf install httpd, php, mariadb, php-mysqlnd
3.add website to /var/www/html/ or set up directory listing if it is meant to be a file server
4.Obtain WordPress from official website and add it if you so prefer following their guide, which is explained far better than mine: https://www.wpbeginner.com/
5.If you would like to set up an automated ftp user creation with proper permissions and chroot, view my guide here: https://github.com/piluvr/ftp-apache2
