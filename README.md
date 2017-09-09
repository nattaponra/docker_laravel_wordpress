# What is docker_laravel_wordpress?
The docker_laravel_wordpress is docker-compose scritp for create an environment of development and deployment.
for easy simulate environment with docker technology.

# Which is docker_laravel_wordpress include?
## 1. Nginx
nginx [engine x] is an HTTP and reverse proxy server, a mail proxy server, and a generic TCP/UDP proxy server, originally written by Igor Sysoev. For a long time, it has been running on many heavily loaded Russian sites including Yandex, Mail.Ru, VK, and Rambler. According to Netcraft, nginx served or proxied 29.25% busiest sites in August 2017. Here are some of the success stories: Netflix, Wordpress.com, FastMail.FM.
## 2. PHP-FPM
PHP-FPM (FastCGI Process Manager) is an alternative PHP FastCGI implementation with some additional features useful for sites of any size, especially busier sites.
## 3. MYSQL
MySQL is an open-source relational database management system (RDBMS).Its name is a combination of "My", the name of co-founder Michael Widenius's daughter, and "SQL", the abbreviation for Structured Query Language. The MySQL development project has made its source code available under the terms of the GNU General Public License,
## 4. phpMyAdmin
phpMyAdmin is a free software tool written in PHP, intended to handle the administration of MySQL over the Web. phpMyAdmin supports a wide range of operations on MySQL and MariaDB. Frequently used operations (managing databases, tables, columns, relations, indexes, users, permissions, etc) 


# How to use it?
## Step 1: Install docker first.
You can read how to install docker in docker official website follow below link
https://docs.docker.com/engine/installation/ 

## Step 2:Clone a docker_laravel_wordpress to your computer.
Clone by HTTPS:
```
https://github.com/nattaponra/docker_laravel_wordpress.git
```
Clone by Git clone:
```
git clone https://github.com/nattaponra/docker_laravel_wordpress.git
```

If you finish clone,you will see these files.
* docker-compose.mly
* dockers

## Step 3: Changes docker directory mode to allow docker use volumes.

```
cd docker_laravel_wordpress
chmod -R g+rwX dockers
```
