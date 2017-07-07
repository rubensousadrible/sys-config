# Setup Let's Encrypt With Apache on Ubuntu 14.04

Let's Encrypt is a new certificate authority that allows you to issue SSL certificates for free. You can now use SSL without any extra costs. When using an SSL certificate, all traffic between the client and the server is encrypted -- which drastically improves your website security.

This guide covers the installation of a Let's Encrypt certificate and automatic renewal on Ubuntu.

By the end of this tutorial you will have an Apache server setup on Ubuntu 14.04 with Let's Encrypt.

## Step 1: Prerequisites

You will need a Vultr SSD cloud server with Ubuntu 14.04 installed. You will also need a LAMP stack (Apache, PHP, etc.). If you do not yet have a LAMP stack installed on your Vultr server, please refer to the following knowledge base article: [How to Install Apache, MySQL, and PHP on Ubuntu](https://www.vultr.com/docs/how-to-install-apache-mysql-and-php-on-ubuntu).

Once you have a working LAMP Stack on your Ubuntu Server, you can proceed with with installing Let's Encrypt.

In order to generate and install your SSL certificate, you will need `Git` to clone the Let's Encrypt repository:

`$[ubuntu] apt-get install git
$[ubuntu] git clone https://github.com/letsencrypt/letsencrypt /opt/letsencrypt`

This will download the Let's Encrypt installer to `/opt/letsencrypt`.
